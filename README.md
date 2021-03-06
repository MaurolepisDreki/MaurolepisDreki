<div align="right">
  <a href="https://www.buymeacoffee.com/MaurolepisDreki" alt="Show your support @ https://www.buymeacoffee.com/MaurolepisDreki">
    <img src="https://img.buymeacoffee.com/api/?url=aHR0cHM6Ly9pbWcuYnV5bWVhY29mZmVlLmNvbS9hcGkvP25hbWU9TWF1cm9sZXBpcytEcmVraSZzaXplPTMwMCZiZy1pbWFnZT1ibWMmYmFja2dyb3VuZD0yNkIwQTE=&creator=Maurolepis+Dreki&is_creating=raising%20the%20bar%20of%20software%20quality%20through%20Human%20Centered%20Design&design_code=1&design_color=%2326B0A1&slug=MaurolepisDreki" style="width: 15vw; height: auto;">
  </a>
</div>

# Who Are You?
Everybody asks this question, from prospective employers to caterpillars, -- but not administrators because they either <abbr title="ass-u-me">assume</abbr> this knowledge or find you unworthy of notice, -- and of all the answers that can be given, the only answers we [people] accept are the ones we come up with ourselves, demonstrating the saying "a fructibus eorum cognoscetis eos" [people are known by their results] (Sec. Matt. VII:XVI).  So, rather than answering this question directly, I will reveal something of my designs and let you come to your own conclusions; doing anything else would result in a realization of [Carroll's Paradox](https://wmpeople.wm.edu/asset/index/cvance/Carroll) which demonstrates how it is impossible to forcably compell belief in others.

## Coding Standard
0. ***DO NOT** BE THE REASON FOR THE CREATION OF NEW RULES!!!*  
   I absolutly hate following rules like these and have come to consider them as Machiavelli's cruelties: an occasionally nessisary evil to be skillfully
   employed with extream rarity and swiftly executed with extream prejudice.  As a fellow computational artist, I would prefer to maintain a freedom of
   expression, but that must come thrid to run-time efficiency and ledgeability, respectively.
1. All blocks must be opened on the same line as the statement they are part of.  
   ```C++
   if( /* expr */ ) {
      /* stmts */
   }
   ```
2. Not all blockable statements require blocks.  
   ```C++
   if( /* expr */ )
      /* stmt */
   ```  
   Neither do such statements require newlines except where the code is made more ledgable by that whitespace.  
   ```C++
   if( /* expr */ ) /* stmt */
   ```  
   The most common case of this is the joining of `else` and `if` which are two seperate blockable statements.  
   ```C++
   if( /* expr */ ) {
      /* stmts */
   } else if( /* expr */ ) {
      /* stmts */
   }
   ```
3. `else` statements must appear on the same line as the previous statement's closing brace.  
   ```C++
   if( /* expr */ ) {
      /* stmts */
   } else {
      /* stmts */
   }
   ```
   But only where applicable.  
   ```C++
   if( /* expr */ )
      /* stmt */
   else {
      /* stmts */
   }
   ```
   And unless there is a good reason (like appropriate interceeding documentation) not to.
   ```C++
   if( /* expr */ ) {
      /* stmts */
   }
   
   /* <some commentary here> */
   else {
      /* stmts */
   }
   ```
4. The names of any function must be immedideately followed by the `(` token (no preceeding whitespace) and followed by either a space (not a tab), a newline, or the reciprical `)` token where applicable (declarations, definitions, and invocations).  Also the `)`token should be preceeded by a space or a newline whenever the `(` token is followed by one.
   ```C++
   void help();
   
   int main( int argc, char **argv ) {
      /* stmts */
   }
   ```
   NOTE: In the case of niladic functions (zero parameters), it is never appropriate to put whitespace between the `(` and `)` tokens.
5. `while`, `for`, `if`, and `switch` are to be reguarded as built-in functions, meaning that the same rules apply for placing their expression statements.

## Code of Conduct
> The estate all men are naturally in is a state of perfect freedom to order their actions and dispose of their possessions and personel as they think fit (within the bounds of the Laws of Nature) without asking leave or depending upon the will of any man.
> 
> This state is also one of equality, wherein all the power and jurisdiction is reciprocal, no one having more authority than any other.  There is nothing more evident than that creatures of the same specices, promiscuoualy born to all the same advantages of Nature and using those same faculties, are also equal one unto another without any sense of subordination or subjegation.
> 
> &nbsp;~ John Lock (1690 A.D.), *An Essay Concerning The True Original Extent And End of Civil Government*, Chapter II <br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*{Language updated to Contemporary American English}*

These words formed the original inspiration of these United States, justifying not only the Colony's open rebellion against their sovereign, King George III and the British Parliament, by The Unanimous Declaration of The Thirteen United States of America (The Declaration of Independance), -- which paraphrases these same words as "We hold these truths to be self-evident: that all Men are created equal, ...", but also the origional pilgrimage from England by the Puritans who were driven out for having similar ideas about living by the Laws of Nature as established by Nature's God which does not place any Man as having authority over any other (see also *The Ninety-Five Thesis* which accuses the Church of assuming the authority of damnation in contradiction to their own scriptures).

I too am of a similar mind, after the pattern described by Locke, as every true son and daughter of these United States is.
My conduct and philosophy is always in accordance the bounds of the Laws of Nature which unbinds Liberty to any action that neglects to bind the Liberty of others, or serve to compel them in any way, while restricting the definition of Property, -- the ownership and control of things, -- to that which [first] is improved by his labors, or otherwise fairly traded for at equal value, and [second] is within his immediate power to use or consume such that it does not loose it's value by it's dissuse and eventual obselecence.
This philosophy causes two major deviations from the world we know: first, it strikes out all notions of Intelectial Property on the grounds that knowledge is an infinite resource that, once shared, is no longer the sole property of its originator and becomming the respective properties of any and all who do know it, and obligating them to either use it or share it themselves before it turns to waste.
And second, and most noticably, it atomically dismantles all notions of heirarchy and lays waste to pride by delivering a solomn Memento Mori to all those beleiving themselves so entitled to a pedestal by which they derive any entitlement to unearned, or lost, respect.

The state of War stands in contrast to the state of Nature, both states existing according to their own law: the state of Nature existing when the Laws of Nature are abided, and the state of War existing when any one of those laws are remotely infringed upon or violated.
Unlike many, I am not opposed to war, rather I have sought to master its Art in every aspect and continue to promote that others do the same: we [people] believe, as demonstrated by our actions, that the only thing that keeps evil at bay is the fear of consequences for their actions as codified into policy.  This does two things: one, it creates a dependence on those whome we trust to create and enforce those policies on our behalf, and second, it immunizes those creators and those elite they choose to benifit from consequences by legalizing thier crimes against humanity accoridng to the laws of Nature by the policies they create.
If we, the people, all sought to master The Art of War, many of our problems would go away overnight: theives would either turn honest or dissapear rather than risk death or worse for their trouble, and the same with abusers, rapists, &c., and all because we empowered the individual against those who designed to do them harm.

Many who find this notion appauling would cite that killing these people makes us no better then they are; I applaud such persons who would so charitably allow their bodies, livelyhoods, possessions, and liberties to be violated, -- the very fact you exist reduces the chance that the rest of us will be so violated because these poor, misunderstood, needy persons have such avenues where they can act upon their depravities without fear, -- but let anyone who is not of this mind arm themselves and strike the fear of death and pain into their hearts such that we will drive them into your loving arms.
What makes us better then they is that what we do is not done in depravity, but out of nessessity for ourselves, those in our care, and for all that we hold dear, and we will do these things even at the risk of your wrath becaues it is justice, -- not Plato's perverted definition of justice, but the true justice of Nature's God written in the whitespace behind "an eye for an eye", -- so when it is done, it is because it had to be done.


# Why Pair?
## Quality
Relates to [Definition of Done](https://www.agilealliance.org/glossary/definition-of-done/)
If each of us notices errors and opportunities abiut 90% of the time, a pair would miss them 1% of the time while a solo would miss 10% of the time.

# Resources
 
## [Pair Programming Styles](http://articles.coreyhaines.com/posts/thoughts-on-pair-programming)
 
## [Pair Programming Cheat Sheet](http://www.solutionsiq.com/pair-programming-cheat-sheet/)
Pair Programming Tips - The 7 Synergistic Behaviors  
* Pair Pressure – Positive encouragement = not wanting to let partner down + satisfaction of working harder & smarter than you would alone  
* Pair Negotiation – Combining two sets of skills for design & implementation to yield the best solution that fits  
* Pair Courage – Advantage of not being alone in a challenging task, trying together what you might not alone  
* Pair Review – Continuous review of design & implementation that happens in context and is more likely to be acted upon  
* Pair Debugging – Going from problem identification to fix in a more enjoyable and often far shorter way than an individual might do it  
* Pair Learning – Acquiring and/or improving skills while delivering value through working with another  
* Pair Trust – Becoming more confident in each other’s skills and communication to present the best ideas because they feel supported  
 
## [10 Ways to Improve Your Pairing Experience](https://www.thoughtworks.com/insights/blog/10-ways-improve-your-pairing-experience)
1. Do not centralize driving
2. Manage the focus together
3. Avoid working alone
4. Alternate moments of concentration and relaxation
5. Celebrate your achievements!
6. Synchronize with your partner
7. Give context appropriately
8. Learn to deal with disagreements
9. Be ready to learn and to teach
10. Give and receive feedback when you're done

## [Pair Programming: Observations on anti-patterns](http://www.markhneedham.com/blog/2009/08/27/pair-programming-observations-on-anti-patterns/)
* Moving around the code too quickly
* Not listening to other solutions
* Grabbing the keyboard away
 
# The Roles
## Driver
* Has the keyboard and implements code.
* Think tactically. Focus on the here and now.
* Focus on “Just coding”. Always Be Closing.
* Help the pair go fast.
* Yagni. You ain't gonna need it, so don't worry about it.
* Get the story done.
* Outer-inner dialog. Talk about what you are thinking and doing. Make sure that your pair can keep up.
* Avoid rabbit holes and interruptions.

## Navigator
* Isn't writing code. =(
* Think strategically. Focus at higher levels of scope. Think about how our work fits into the broader design. How does our work affect future features or concepts.
* Focus on "going well". Quality should always be on your mind.
* Help the pair go slow enough to do things right.
* Backstop your pair. They will miss important things. Make sure you are paying close attention so you can catch what they drop.
* Get a high quality result.
* Be meta. Make sure that the pair is effective. Bring up ways for the pair to work better.
* Take notes about items that the pair needs to come back to. "Rename class Foo to something better". This is how you keep the pair on track and avoid interruptions and going down rabbit holes.

# Patterns
_Ping-Pong_: One member of the pair writes a failing unit test. The second member writes production code to make the test pass, and then writes the next unit test. The first member writes production code to make that test pass, and then writes the next unit test. The pair continues in the same way to solve the problem. The ping-pong style is usually applied when two peers are working on a problem together.

_Take Breaks_: Frequently (at least once per hour), stand up and disengage from your work. This will make you more effective since it allows your mind and body to reset and be more prepared for work. See Pomodoro Technique.

_Discuss higher level concepts together_: At least occasionally put on different hats (as a pair) and reflect on where your work is at and where it is going. Put on your architect hat and think about how your code fits into the broader design. Put on your QA hat and consider the edge cases of your story and what it means for your story to be "done done". Consider drawing a small UML diagram of the current state of your design and another possible design.

_Switch pairs frequently_: At the very least switch pairs when you complete each story. Also consider switch pairs every morning or even in the morning and after lunch. It's possible for a team to be effective switching pairs every hour.

_Going Meta_: Discuss what is working for you and what isn't working so well. Have a 5 minute retro with your pair. Use this information to change how the two of your pair together. Communicate!
 
# Anti-patterns
_Superman_: They refuse to be impaired by a slow partner. They hog the keyboard and save the world all on their own.

_Anti-Mentor_: As navigator, this senior developer leaves their junior partner without guidance.

_Semi-Colon Pair -or- Backseat Driver_: Calls out typos, keyboard shortcuts, doesn't wait for you to complete your thoughts in code.

_Moving around the code too quickly_: One thing that we often forget is that when we're driving we know exactly where we're going with the mouse or keyboard just before we do it whereas the other person doesn’t know until we've done it. As a result of this, it is useful to commentate on what we're about to do and not move around the code at break neck speed, but instead take our time and pause after each step to allow our pair to follow where we are in the code.

_Not listening to other solutions_:  Thinking that you personally have the solution to all the problems the pair encounters and that your solution should always be the one used.

_Strong code ownership_: It's often very hard to motivate people to care about code they aren't responsible for.

_Inconsistent workstation setup_: People like to work in their own environment. Unfortunately, when pairing you are unlikely to find two people who agree on what an environment should be.

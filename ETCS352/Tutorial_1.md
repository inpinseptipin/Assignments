# Tutorial 1
Write a brief about XP ( Extreme Programming ) practices in the Agile Model

# Answer

## Definition
Extreme Programming is a discipline of software development based on values of simplicity, communication, feedback, courage, and respect. It works by bringing the whole team together in the presence of simple practices, with enough feedback to enable the team to see where they are and to tune the practices to their unique situation.

There are various XP practices , they are as follows 

  1. The Planning Game
  2. Small Releases
  3. Metaphor
  4. Simple Design
  5. Testing
  6. Refactoring
  7. Pair Programming
  8. Collective Ownership
  9. Continuous Integration

## Planning Game

XP planning addresses two key questions in software development: predicting what will be accomplished by the due date, and determining what to do next.The emphasis is on steering the project – which is quite straightforward – rather than on exact prediction of what will be needed and how long it will take – which is quite difficult. There are two key planning steps in XP, addressing these two questions:

### Release Planning
It is a practice where the Customer presents the desired features to the programmers, and the programmers estimate their difficulty. With the cost estimates in hand, and with knowledge of the importance of the features, the Customer lays out a plan for the project.

### Iteration Planning
It is a practice whereby the team is given direction every couple of weeks. XP teams build software in two-week “iterations”, delivering running useful software at the end of each iteration.

## Small Releases
XP teams practice small releases in two important ways:

### First
the team releases running, tested software, delivering business value chosen by the Customer, every iteration. The Customer can use this software for any purpose, whether evaluation or even release to end users (highly recommended). The most important aspect is that the software is visible, and given to the customer, at the end of every iteration. This keeps everything open and tangible.

### Second
XP teams release to their end users frequently as well. XP Web projects release as often as daily, in house projects monthly or more frequently. Even shrink-wrapped products are shipped as often as quarterly.


## Metaphor
XP Porgramming teams develop a common vision on how the product will work. This vision is called as a metaphor. In simple terms , the metaphor is a description of how a program will work. XP teams use a common system of names to be sure that everyone understands how the system works and where to look to find the functionality you’re looking for, or to find the right place to put the functionality you’re about to add.

## Simple Design
XP teams build software to a simple but adequate design. They start simple and through the use of programmer testing and design improvements, they keep it that way. An XP team keeps the design exactly suited for the current functionality of the system. There is no wasted motion , and the software is already ready for what's next.

## Pair Programming
All production software in XP is built by two programmers, sitting side by side, at the same machine. This practice ensures that all production code is reviewed by at least one other programmer, and results in better design, better testing, and better code.

Pairing, in addition to providing better code and tests, also serves to communicate knowledge throughout the team. As pairs switch, everyone gets the benefits of everyone’s specialized knowledge. Programmers learn, their skills improve, they become more valuable to the team and to the company. Pairing, even on its own outside of XP, is a big win for everyone.

## Refactoring
Extreme Programming focuses on delivering business value in every iteration. To accomplish this over the course of the whole project, the software must be well-designed. The alternative would be to slow down and ultimately get stuck. So XP uses a process of continuous design improvement called Refactoring

The refactoring process focuses on removal of duplication (a sure sign of poor design), and on increasing the “cohesion” of the code, while lowering the “coupling”. High cohesion and low coupling have been recognized as the hallmarks of well-designed code for at least thirty years. The result is that XP teams start with a good, simple design, and always have a good, simple design for the software. This lets them sustain their development speed, and in fact generally increase speed as the project goes forward.

## Continious Integration
Infrequent integration leads to serious problems on a software project. 
### First
Although integration is critical to shipping good working code, the team is not practiced at it, and often it is delegated to people who are not familiar with the whole system. 
### Second
Infrequently integrated code often results in buggy code. Problems creep in at integration time that are not detected by any of the testing that takes place on an unintegrated system. 
### Third
Weak integration process leads to long code freezes. Code freezes mean that you have long time periods when the programmers could be working on important shippable features, but that those features must be held back. This weakens your position in the market, or with your end users.

Therefore Continious Integration is required to prevent the problems underlined above.

## Collective Code Ownership
On an Extreme Programming project, any pair of programmers can improve any code at any time. This means that all code gets the benefit of many people’s attention, which increases code quality and reduces defects.

When code is owned by individuals, required features are often put in the wrong place, as one programmer discovers that he needs a feature somewhere in code that he does not own. The owner is too busy to do it, so the programmer puts the feature in his own code, where it does not belong. This leads to ugly, hard-to-maintain code, full of duplication and with low (bad) cohesion.

## Customer Tests
As part of presenting each desired feature, the XP Customer defines one or more automated acceptance tests to show that the feature is working. The team builds these tests and uses them to prove to themselves, and to the customer, that the feature is implemented correctly. Automation is important because in the press of time, manual tests are skipped.

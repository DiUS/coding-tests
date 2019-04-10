DiUS is starting a bowling club. To help with the club, we have engaged you to program a scoring system. 

The features on the system are:

* One player only
* In each frame, the bowler has 2 tries to knock down all the pins
* If in 2 tries, the bowler fails to knock down all the pins, their score is the sum of the number of pins they've knocked down in the 2 attempts

E.g, if a bowler rolls, 4,4

Their score is 8.  

* If in 2 tries, the bowler knocks down all the pins, it is a spare. The scoring of a spare is the sum of the number of pins knocked down plus the number of pins knocked down in the next bowl.

E.g, if a bowler rolls, 4,6 |  5, 0

Their score is 20. So that's (4 + 6 + 5) + (5 + 0)

* If in one try, the bowler knocks down all the pins, it is a strike. The scoring of a strike is the sum of the number of pins knocked down plus the number of pins knocked down in the next two bowls.

E.g, if a bowler rolls, 10 | 5, 4

Their score is 28. So that's (10 + 5 + 4) + ( 5 + 4)

* There are 10 pins in a frame
* There are 10 frames in a match
* Don't worry about validating the number of rolls in a frame

The interface should look like this (in Java);


```java
bowlingGame.roll(noOfPins);
bowlingGame.score();
```

OPTIONAL
--------

If time permits implement the rules for the last frame (i.e, 10th frame)

* In the last frame, if the bowler bowls a spare, they get another bowl. The score of this frame is the sum of the three bowls.
* In the last frame, if the bowler bowls a strike, they get another 2 bowls. The score of this frame is the sum of the three bowls
* If one has a strike for every roll, their score is 300

Notes on implementation:

- use **Java, Javascript, TypeScript, Ruby, Kotlin, Python, Swift, or Groovy**
- try not to spend more than 2 hours maximum. (We don't want you to lose a weekend over this!)
- don't build guis etc, we're more interested in your approach to solving the given task, not how shiny it looks
- don't worry about making a command line interface to the application
- don't use any frameworks (rails, spring etc), or any external jars/gems (unless it's for testing or build/dependency mgt)

When you've finished, send through the link to your github-repo. Happy coding

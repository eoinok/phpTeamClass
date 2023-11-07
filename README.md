# Week 6 Lab

Clone this repo into your www folder under laragon. In the command prompt cd into the \laragon\www folder. Make sure that you are in the correct folder and that laragon\www appears in the command prompt. Type git clone your-repo-url (Get your repo url from github after creating the repo). Then cd into the folder you have just cloned by typing cd week6Lab-yourgithubid. Once you are in the correct folder, keep this command window open so you can type in your git commands as required.

This lab includes a number of steps to create a new PHP class to control football Teams and their results. By the end of this lab students will be able to:

- create a PHP class from a UML description
- Take values from a HTML form and use them to instantiate the Team class
- use the methods of the Team class to process data relating to the Team

# Part 1

Create a PHP file containing the following UML class. Assume the constructor takes the team name as a parameter. The finalScore method indicates the score of a match played against an opposing team. The first parameter of the final score method indicates the team's score in the game. The second parameter indicates the opposing team's score. Using this method it is possible to calculate whether the Team won lost or draw. Based on this, the finalScore method should add three points to the total points if the team won. One point should be added for a draw and no points should be added for a loss. In addition to calculating points the finalScore method should add the goals scored (from the first parameter) to the totalsGoals attribute. The finalScore method should also increase the totalGames by one.
![A UML description of Team.php class](./TeamUML.jpg)

When you have completed the Team.php class save it to your repo folder and test it using the PHP tester class. To do this type ***blah blah blah*** into the Command Line Interface. 

# Part 2

Add a method called getGoalAverage() to your class as follows
![A UML description of a Team class with a getGoalAverage function](./TeamUMLwithGoalAverage.jpg)

The goal average should merely return the average number of goals scored so far this season. This is the total number of goals divided by the total number of games. Bear in mind that these figures are available as attributes of the class but to access them you must use $this together with the arrow operator.



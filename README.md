# rockpaperscissors
CS304 Portfolio
Holly Weatherbee

TABLE OF CONTENTS

*Introduction
*File List
*Installation
*Design
*Author


# INTRODUCTION
================================================
This is a C++ program that emulates a game of Rock, Paper, Scissors.  It is a two player game in which the user plays against the computer.   In this game, there are 3 weapons: Rock, Paper, Scissors.  Each player chooses a weapon.  If both players select the same weapon, the game is a tie.   For non-tying choices, the winner is determined as follows:
              * ROCK blunts SCISSORS, so the player who selects ROCK wins.
              * PAPER wraps ROCK, so the player who selects PAPER wins.
              * SCISSORS cuts PAPER, so the player who selects SCISSORS wins.

The program asks if the user would like to play a game.  If the user input is ‘Y’ for yes, the instructions are displayed for Rock, Paper, Scissors.   A request for the user input of ‘R’ for Rock, ‘P’ for Paper, or ‘S’ for Scissors is also displayed.  The program then compares the user’s input to that of a randomly generated computer choice to determine the winner and displays the player choices and explains the outcome.   An option to play again is displayed.  If the player chooses to play again, the process above repeats.  If the player chooses NOT to play again, a tally of ties, wins and losses will be displayed.

# FILE LIST
================================================
Lab3_RockPaperScissors_Weatherbee.cpp
Lab3_RockPaperScissors_Weatherbee.exe


#  INSTALLATION
================================================
This program requires Dev C++, which may be downloaded from www.bloodshed.net and installed as directed on that site.

Once installed, open Dev C++.   From the File menu, navigate to the location of the Lab3_RockPaperScissors_Weatherbee.exe file to open the Rock, Paper Scissors game.

# DESIGN
=====================================================================================

The types of coding that I knew I would need for this program were:
     •	An enumerated list of available weapons
     •	Function to randomize the computer weapon choice
     •	Function to convert the user input to a weapon choice that could be used for comparison
     •	Function to compare the player choices
     •	Function to calculate wins, losses and ties
     •	Function for game instructions
     •	Function for game result display


I utilized the following C++ libraries to begin this program:
     *	<iostream>
     *	<string>
     *	<list>
     *	<cstdlib>
     *	<ctime>
     *	<iomanip>

When I began thinking about how to create this program, I started with a hand drawing of the overall functions that I needed.  I wrote a list of all data types needed to perform the functions under each function.   From this drawing, I began to declare the data types and name them.   I began to code this program knowing that much of the program would be based on the choice of weapon and created an enumerated list that contained the weapons.  I knew that I would need that this list would need be specific to both the player and the computer with a method to marry the input of the user and randomization of the computer choice for comparison.  

By utilizing the rand function in the ctime library, with the parameter of 3 (for the number of members in the weapon list) and comparing it to the enumerated weapon list, I had secured a method to convert the integer result of the rand into a string data type.  I converted the user’s char input into a string, allowing the capability to compare these two unlike data types.   I used this comparison to predict the game result and display the appropriate results and game tallies.

I found I had the most difficulty in how to code the actual game result.  I tried to do this without actually drawing this out with pen and paper or just simply putting the items into a spreadsheet and analyzing the possible combinations visually. Also, I was so focused on the syntax and structure of the programming language that I was overwhelmed to the point of ineptitude.  There were seven possible outcomes to the game.  I failed to see the simplicity because I assumed it was more complicated than I initially imagined.

I learned that I need to trust my own method of problem solving, first and foremost. I can learn to apply any programming language, if I know how to solve the problem or know where to discover the solution.  

# AUTHOR
==================================================================================================
Holly Weatherbee
jsu5101a@stu.jsu.edu


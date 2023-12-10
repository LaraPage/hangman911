# Hangman: An AiCore project for beginner coders

## Description

Hangman is a classic game in which a player thinks of a word and the other player tries to guess that word within a certain amount of attempts. This is an implementation of the Hangman game, where the computer thinks of a word and the user tries to guess it. 

This project uses guidelines and a template given by AiCore to develop the program. It is split into five  milestones to make it readable and manageable for a beginner to follow.

During this project, the core skills and principles of Python are developed and practiced. The skills developed are as follows:

- Object Oriented Programming (OOP)
- Familiarisation with GitHub and Visual Code Studio
- Implementing classes, funtions, methods and data structures

## Milestone 1

The program environment is set up. A GitHub repository is created using the template given that provides a structure for the project. The milestones and tasks are clearly set out.

## Milestone 2

The list of possible words is created consisting of five fruits then a fruit randomly selected via importing the random.choice method. The user is asked to provide an imput defined as guess and an if/else statement used to ensure that this guess is only one letter.

## Milestone 3

This milestone is used to check if the guessed letter is in the randomly selected word. Two funtions are created to contain the code for this. The check_guess function takes the guessed letter as an argument and checks if the letter is in the word. The ask_for_input function contains a while loop that continuously asks the user for an imput and validates it.

## Milestone 4

In this classThe OOP paradigm is utilised to create the hangman class and develop the complete hangman game. The __init__ method is created to initialise the attributes of the class in which the word_list and num_lives are passed as parameters. What happens when the guessed letter is and is not in the word is also developed.

## Milestone 5

In this milestone the logic of the game is coded. The function play_game is created where the word_list is passed a parameter and an instance of the hangman class is created. Whether the number of lives is zero will decide whether the user has won or lost.

## Installation and usage instructions

This game is a command line application and can be executed using Python3. The user enters letters to guess the randomly selected fruit after the number of letters in the fruit is presented.

## License information

This work was created via the AiCore program and the public template provided.


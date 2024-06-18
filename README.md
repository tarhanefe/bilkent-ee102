<h1 align="center">Bilkent University EE102 - Introduction to Digital Circuit Design Labs and Project</h1>

<p align="center">Bilkent University EE102 Course Labs and Project of 2021-2022 Fall Semestr offered by Cem Tekin. The codes were wrtitten using VHDL.</p>

<p align="center">
  <img src="https://github.com/tarhanefe/bilkent-cs115-labs/assets/73281981/353e59fa-4cf5-4be5-b62f-afa383f3fdcd" alt="Bilkent University Logo" width = "300" />
</p>


# Project

The primary goal of this project is to develop a digital game, Whack-A-Mole, using a VGA connector and a BASYS3 FPGA. The project aims to enhance digital design abilities, focusing on debugging, glitch removal, and the implementation of sequential and combinatorial design elements to create a glitch-free game.

## Design Specifications:

- Components used: BASYS3 FPGA, VGA monitor, VGA cable, mini-breadboard, buzzer, jumper cables.
- Game concept: Adaptation of the classic arcade game Whack-A-Mole, where players hit moles (represented by colored squares) to score points.
- Game mechanics: Players gain points by hitting moles and lose points for errors. The game features two difficulty levels (easy and hard), sound effects using a buzzer, and a game clock.

## Methodology:

- VGA_TOP: Main module connecting all submodules, setting the screen saver using a multiplexer.
- Clock Divider and Random Clock Divider: Generate desired clocks from the BASYS3’s built-in clock.
- VGA_640x480: Creates horizontal and vertical count signals and sync signals for the monitor.
- Game Buzzer: Generates a beep sound when buttons are pressed.
- Whack-A-Mole Module: Controls the game process using a Moore FSM with states for game start, gameplay, and game over.
- Push Release: Detects changes in button states to avoid repetition errors.
- Main Game Screen: Draws squares on the display and handles their blinking effect.
- Game Clock: Displays the time elapsed since the start of the game using FSMs.
- Game Mode: Displays the game mode and score on the screen.
- Character Placer and Alnum: Place alphanumeric characters and symbols on the screen.
- Game Sounds: Displays the audio status on the screen.
- Score Count: Manages the game score and determines game over conditions.
- LFSR4: Generates random numbers for the game.
- Game End/Begin: Displays the start and end screens using word selectors and multiplexers.

## Project Documents:


- [Project Proposal](https://github.com/tarhanefe/bilkent-ee102/blob/main/Project/Proposal/Efe%20Tarhan%20EE102%20Project%20Proposal.pdf)
- [Project Final Report](https://github.com/tarhanefe/bilkent-ee102/blob/main/Project/Final%20Report/EFE%20TARHAN%20EE102%20TERM%20PROJECT%20REPORT.pdf)
- [Project Codes](https://github.com/tarhanefe/bilkent-ee102/tree/main/Project/Code%20File)




# Labs

## Lab 1

Lab 01 focuses on input/output operations and arithmetic expressions. Students write Python scripts to calculate results from user input, determine the win percentage of a basketball team, format personal details, and convert feet and inches to centimeters.

- [Lab 1 Guideline](https://github.com/tarhanefe/bilkent-ee102/blob/main/Labs/Lab%201/lab1.pdf)
- [Lab 1 Report](https://github.com/tarhanefe/bilkent-ee102/blob/main/Labs/Lab%201/Efe%20Tarhan%20Lab%201%20Report.pdf)


## Lab 2

Lab 02 involves practicing conditional statements, loops (for and while), and string manipulations. Students validate triangle sides, calculate net income after tax, calculate powers of 2, and manipulate strings to remove non-alphanumeric characters.

- [Lab 2 Guideline](https://github.com/tarhanefe/bilkent-cs115-labs/blob/f3ade88133d8ff76e9ee67376222880cd653694a/Lablar/Lab%202/Lab02New.pdf)
- [Lab 2 Code](https://github.com/tarhanefe/bilkent-cs115-labs/blob/f3ade88133d8ff76e9ee67376222880cd653694a/Lablar/Lab%202/Efe%20Tarhan%20CS115-%20Lab%202.zip)


## Lab 3

Lab 03 focuses on functions in Python. Students create functions for string manipulation, generate hailstone sequences, and calculate the sum of digits in a range of numbers.

- [Lab 3 Guideline](https://github.com/tarhanefe/bilkent-cs115-labs/blob/f3ade88133d8ff76e9ee67376222880cd653694a/Lablar/Lab%203/Lab03.pdf)
- [Lab 3 Code](https://github.com/tarhanefe/bilkent-cs115-labs/blob/f3ade88133d8ff76e9ee67376222880cd653694a/Lablar/Lab%203/Lab03_Tarhan_Efe.zip)


## Lab 4

Lab 04 introduces string manipulation, file handling, and modules. Students create functions to pluralize words from an input file and write the pluralized words to an output file.

- [Lab 4 Guideline](https://github.com/tarhanefe/bilkent-cs115-labs/blob/3a130b33cfc0fc15cee8f8fe6e489f8ddef684c3/Lablar/Lab%204/Lab04.pdf)
- [Lab 4 Code](https://github.com/tarhanefe/bilkent-cs115-labs/blob/3a130b33cfc0fc15cee8f8fe6e489f8ddef684c3/Lablar/Lab%204/Lab04_Tarhan_Efe.zip)


## Lab 5

Lab 05 covers tuples, lists, and dictionaries. Students estimate the value of ‘e’ using a series, separate elements by type in a list, and form a sentence from words in a file based on their positions.

- [Lab 5 Guideline](https://github.com/tarhanefe/bilkent-cs115-labs/blob/3a130b33cfc0fc15cee8f8fe6e489f8ddef684c3/Lablar/Lab%205/Lab05.pdf)
- [Lab 5 Code](https://github.com/tarhanefe/bilkent-cs115-labs/blob/3a130b33cfc0fc15cee8f8fe6e489f8ddef684c3/Lablar/Lab%205/Lab05_Tarhan_Efe.zip)


## Lab 6

-	Lab 06  focuses on two-dimensional lists and numpy arrays. Students write functions to manipulate 2D lists and use numpy arrays to process data from files without using loops.

- [Lab 6 Guideline](https://github.com/tarhanefe/bilkent-cs115-labs/blob/b9ab1ee21a216458c1c0493e65c0bd316f04b686/Lablar/Lab%206/Lab06%20(2).ipynb)
- [Lab 6 Code](https://github.com/tarhanefe/bilkent-cs115-labs/blob/b9ab1ee21a216458c1c0493e65c0bd316f04b686/Lablar/Lab%206/05_Lab06_Tarhan_Efe.zip)


## Lab 7

Lab 07 focuses on classes in Python. Students create a Stock class with various attributes and methods, including initializing, getting, and setting values, as well as representing the stock information.

- [Lab 7 Guideline](https://github.com/tarhanefe/bilkent-cs115-labs/blob/b9ab1ee21a216458c1c0493e65c0bd316f04b686/Lablar/Lab%207/Lab07%20(2).pdf)
- [Lab 7 Code](https://github.com/tarhanefe/bilkent-cs115-labs/blob/b9ab1ee21a216458c1c0493e65c0bd316f04b686/Lablar/Lab%207/Lab07_Efe_Tarhan.zip)


## Lab 8

Lab 08 covers inheritance in Python. Students create a Patient class and an Outpatient subclass, implementing attributes, methods, and functionality for calculating and displaying hospital fees.

- [Lab 8 Guideline](https://github.com/tarhanefe/bilkent-cs115-labs/blob/b9ab1ee21a216458c1c0493e65c0bd316f04b686/Lablar/Lab%208/Lab08%20(2).pdf)
- [Lab 8 Code](https://github.com/tarhanefe/bilkent-cs115-labs/blob/b9ab1ee21a216458c1c0493e65c0bd316f04b686/Lablar/Lab%208/Lab08_Tarhan_Efe.%20(1).zip)


## Lab 9

Lab 09 of CS 115 involves advanced Python concepts, integrating multiple topics learned previously and applying them to complex problem-solving tasks.

- Lab 9 Guideline
- [Lab 9 Code](https://github.com/tarhanefe/bilkent-cs115-labs/blob/b9ab1ee21a216458c1c0493e65c0bd316f04b686/Lablar/Lab%209/Lab09_Tarhan_Efe.zip)


## Lab 10

Lab 10 focuses on data visualization using matplotlib. Students load data from text files, perform data manipulation using numpy, and create plots to visualize the data.

- [Lab 10 Guideline](https://github.com/tarhanefe/bilkent-cs115-labs/blob/b9ab1ee21a216458c1c0493e65c0bd316f04b686/Lablar/Lab%2010/Lab10%20(2).pdf)
- [Lab 10 Code](https://github.com/tarhanefe/bilkent-cs115-labs/blob/b9ab1ee21a216458c1c0493e65c0bd316f04b686/Lablar/Lab%2010/Lab10_Tarhan_Efe%20(1).zip)


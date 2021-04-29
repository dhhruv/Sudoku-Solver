<p align="center">
  <img src="https://github.com/dhhruv/Sudoku-Solver/blob/master/assets/thumbnail.png" width="256" height="256">
  <h2 align="center" style="margin-top: -4px !important;">Why solve Sudoku by hand, when you can write script to solve them for ya ?!</h2>
  <p align="center">
    <a href="https://github.com/dhhruv/Sudoku-Solver/blob/master/LICENSE">
      <img src="https://img.shields.io/badge/license-MIT-informational">
    </a>
    <a href="https://www.python.org/">
    	<img src="https://img.shields.io/badge/python-v3.8-informational">
    </a>
  </p>
</p>
<p align="center">
	<img src="http://ForTheBadge.com/images/badges/made-with-python.svg">
</p>
<p align="center">   
	<a href="https://dev.to/dhhruv/sudoku-solver-a-visualizer-made-using-backtracking-algorithm-5f0d">
    	<img src="https://img.shields.io/badge/dev.to-0A0A0A?style=for-the-badge&logo=dev.to&logoColor=white">
    </a>
</p>

## Introduction:
-	Sudoku is one of the most popular logic-based number-placement puzzle game. The literal meaning of "Su-doku" in Japanese is "the number that is single".

-	The objective is to fill a nine-by-nine (9x9) grid with digits so that each row, column and 3x3 section contain number between 1 and 9, with each number used once and only once in each section. The Sudoku game players are provided with partially filled grid meant to be solved.

-	To solve sudoku one doesn't require the knowledge of mathematics but require the logic and reasoning. Solving Sudoku Puzzles daily helps with your brain. It improves the concentration and logical thinking. One can look for sudoku puzzles given in Newspapers or can play them online provided by many websites. 

## About:

This Script is a Sudoku Solver that solves almost any Sudoku Puzzle by visualizing through the Backtracking Algorithm which is made using the PyGame Library in Python. Ever tried but stucked on Sudoku Puzzles given in newspapers, magazines and online. You can use this script to get its solution instantly and move further.

## Working:

-	Every time this Script is executed, a Random Solvable board is created.
-	Now, the user can first try to attempt solving it by clicking on the cells and entering values manually. Check the Input Section for the same.
-	Once the the user finalizes that the inputted number is the correct entry, pressing the enter key will attempt to input the number onto the board. 
-	Correct answers will be permanently displayed while incorrect answers will be removed. 
-	Likewise, values can be removed by pressing on the backspace or delete keys.

<p align="center">
	<img src="https://github.com/dhhruv/Sudoku-Solver/blob/master/assets/Entering%20Values.gif">
</p>

-	If at any point the player decides to solve the board, the Spacebar key can be pressed.
-	This will commence a visual which will demonstrate how the backtracking algorithm works and how it is being applied in order to solve the board.

<p align="center">
	<img src="https://github.com/dhhruv/Sudoku-Solver/blob/master/assets/Visualizer.gif">
</p>

## Input:

| Keys              | Actions                                                         |
|-------------------|-----------------------------------------------------------------|
| `Left Click`      | Selects the Box to enter a value into that cell.                |
| `Enter`           | Confirms the Value written on the board.     |
| `Backspace/Delete`| Deletes the value in that cell.                                 |
| `Space`           | Solves the Board using the Algorithm.                           |
| `h`               | Gives a Hint. Displays a random correct value on the board.     |

## Requirements:
In order to run the Script, the require **Python & PyGame** and you can install the requirements using:
```
pip install -r requirements.txt
```

## Execution:
-	Clone this repository using
```
git clone https://github.com/dhhruv/Sudoku-Solver.git
```
**OR**
Zip Download the Repository and Extract it's contents.
-	Now run the [SudokuGUI](https://github.com/dhhruv/Sudoku-Solver/blob/master/SudokuGUI.py) file directly in your Terminal using
```
python SudokuGUI.py
```
**OR**
```
python3 SudokuGUI.py
```

<p align='center'><b>Made with ❤ by Dhruv Panchal</b></p>

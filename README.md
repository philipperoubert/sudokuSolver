# sudokuSolver
-- Implementation of Genetic Algorithm to solve sudokus



This program written in python tries to solve sudokus using a genetic algorithm.

The genetic algorithm uses crossover and mutation to be able to find the solution, the fitness function is based on the number of repetition in every row, column and sub-box.

To use it: 

	$ python3 sudoku.py
or

	$ python3 sudoku.py Grid1.ss 100

Note 1: In this example I'm using python3, but if your default python version is above 3.0 then you can use python as well
Note 2: Grid1.ss is the file containing the sudoku grid to be solved, 100 in this case represents the generation population
Note 3: You can edit the grid within the code, a sudoku grid is represented as a list of list

A word on using the code: Feel free to use my code as much as you want as long as you include my name somewhere :) Obviously, if you copy my code, try to understand it!

Some features/changes that could be added/made:
* Change the fitness function to something more complex that doesn't just include repetition of digits
* Implement a feature that would allow different size of sudokus to be solved
* For now the solver only allows a specific grid format to be input, so an idea would be to make the solver recognise what each box looks like rather to base itself on formats so that other grid formats can be input
* Improve the general algorithm to find "obvious" missing digits (i.e.: if a sub-box contains already 8 digits, to add the missing 9th digit)

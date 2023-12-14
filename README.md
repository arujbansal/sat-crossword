# sat-crossword
Using a Boolean Satisfiability solver to create a crossword-puzzle generator in the functional Wolfram Language.

This project was completed as part of the Wolfram High School Research Program 2022. It was published as a "Computational Essay" in the Wolfram Community here: https://community.wolfram.com/groups/-/m/t/2580271

The files in this repository can be opened and will run through Wolfram Mathematica.

## About
This project explores SAT solving as a method for generating crossword puzzles. Relationships between words, letters, and grid cell locations are defined to create crossword puzzles. A "quality" metric is defined based on the final state of the crossword puzzle and a heuristic is used to generate crossword puzzles of better "quality". A crossword grid size and a list of words can be specified and a crossword puzzle containing all the words present in the list can be generated. It is also possible to generate different crossword puzzle word arrangements for the same set of words in some cases.

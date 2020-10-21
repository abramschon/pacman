# Pacman: *Berkeley CS188 Intro to AI Assignment*

## Bram Schönfeldt

This is my completed code for the Search assignment. The report is called `SearchReportBramSchonfeldt.pdf`.

To run the autograder on the code, type:

`python autograder.py`

Note that the default heuristic (*actual distance to furthest bite of food*) for question 7, takes a while to compute
for each step of the algorithm, however, results in a very low number of 'legal expansions'. For a faster
heuristic at the cost of more expansions, I have also defined the *manhattan distance to the furthest bite of food*. Using this
only requires uncommenting line 469 of searchAgents.

More details for the assignment can be found [here](https://inst.eecs.berkeley.edu/~cs188/fa20/project1/)
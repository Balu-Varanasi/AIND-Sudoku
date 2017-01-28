# Artificial Intelligence Nanodegree
## Introductory Project: Diagonal Sudoku Solver

# Question 1 (Naked Twins)
Q: How do we use constraint propagation to solve the naked twins problem?
A: Constraint Propagation uses local constraints to reduce the search space. In Sudoku, since each box allows only one digit to occupy space, when same two digit appears in two boxes, we can conclude that either of a digit can appear in two space. Also, we can reason that no other box, within a unit constraint space can have either of the two digit. This helps us to eliminate possibilities. Thus reducing the search space.

# Question 2 (Diagonal Sudoku)
Q: How do we use constraint propagation to solve the diagonal sudoku problem?
A: To solve the diagonal sudoku problem, we can use the same constraint propagation method as for normal sudoku problems by adding the two diagonal units to the `unitlist` space.

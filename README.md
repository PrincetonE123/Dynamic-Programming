# Dynamic-Programming

Here is the propmt for the programming assignment that was given in class:
1)	Ask the user to specify the total number, n, of all paid tasks.
2)	For each task, ask the user to specify its value (i.e., earning) and duration (i.e., start and end time).
3)	Output all user-specified tasks in a chart or something similar. All tasks need to be sorted by their end times in ascending order.
(Note: If there is any tie, sort such tasks in whatever order of your choice.)
4)	Design three algorithms, i.e., brute-force, recursive DP, and non-recursive DP algorithms, to output all sets of tasks that will maximize the total earning. The output should include the order of these tasks and the total earning as follows.

The time elapsed in the brute-force algorithm is xxx.
The time elapsed in the recursive DP algorithm is xxx.
The time elapsed in the non-recursive DP algorithm is yyy.

Task_x -> Task_y -> Task_z -> …, with a total earning of xxx.
Task_x -> Task_y -> Task_z -> …, with a total earning of xxx.
(Note: There may be more than one set.)
5)	Design your own algorithm to output all maximum legitimate sets of tasks that can be accomplished, i.e., (1) to include as many tasks as possible regardless of the total earning and (2) no two sets can be subsets of each other. The output should include the order of these tasks and the total earning as follows.
There are xxx options to select different sets of tasks.
Option 1: Task_x -> Task_y -> Task_z -> …, with a total earning of xxx.
Option 2: Task_x -> Task_y -> Task_z -> …, with a total earning of xxx.
…
Option xxx: Task_x -> Task_y -> Task_z -> …, with a total earning of xxx.



Here is how the assignment is ran:
The code is run by prompting the user to enter the number of tasks as well as details for each task, such as: value, start time, and end time. The program then sorts the tasks based on the end times, next the three algorithms are applied and the time for each algorithm is calculated. The program then outputs the sorted tasks, then the maximum earning tasks in a set found by each algorithm, and the time taken for each algorithm to execute.


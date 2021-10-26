## 1112 Mice and Maze
A set of laboratory mice is being trained to escape a maze. The maze is made up of cells, and each cell
is connected to some other cells. However, there are obstacles in the passage between cells and therefore
there is a time penalty to overcome the passage Also, some passages allow mice to go one-way, but not
the other way round.
Suppose that all mice are now trained and, when placed in an arbitrary cell in the maze, take a
path that leads them to the exit cell in minimum time.
We are going to conduct the following experiment: a mouse is placed in each cell of the maze and
a count-down timer is started. When the timer stops we count the number of mice out of the maze.
Write a program that, given a description of the maze and the time limit, predicts the number of
mice that will exit the maze. Assume that there are no bottlenecks is the maze, i.e. that all cells have
room for an arbitrary number of mice.
## Input
The input begins with a single positive integer on a line by itself indicating the number of the cases
following, each of them as described below. This line is followed by a blank line, and there is also a
blank line between two consecutive inputs.
The maze cells are numbered 1, 2, . . . , N, where N is the total number of cells. You can assume
that
The first three input lines contain
N ≤ 100. N, the number of cells in the maze, E, the number of the exit
cell, and the starting value T for the count-down timer (in some arbitrary time unit).
The fourth line contains the number M of connections in the maze, and is followed by M lines, each
specifying a connection with three integer numbers: two cell numbers a and b (in the range 1, . . . , N)
and the number of time units it takes to travel from a to b.
Notice that each connection is one-way, i.e., the mice can’t travel from b to a unless there is another
line specifying that passage. Notice also that the time required to travel in each direction might be
different.
## Output
For each test case, the output must follow the description below. The outputs of two consecutive cases
will be separated by a blank line.
The output consists of a single line with the number of mice that reached the exit cell E in at most
T time units.

|   #   | File                       | Description           |
| :---: | -------------------------- | --------------------- |
|   1   | [1112.cpp](./1112.cpp) | main file.            |
|   2   | [11112.pdf](./1112.pdf)   | question pdf          |
|   3   | [banner.txt](./banner.txt) | banner page           |
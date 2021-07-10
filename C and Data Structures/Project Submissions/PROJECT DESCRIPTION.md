## PROJECT DESCRIPTION


Simultaneous equations are those equations involving two or more unknowns that are to have the same values in each equation. They occur as a pair of equations, usually represented by unknowns such as x and y. A sample set of simultaneous set of equations go like the following:

3x+2y=7
5x-3y=37 

 
#### Part 1:

Your task is to develop a C program that will solve two simultaneous linear equations of the above forms using 2 methods:

* Substitution method
* Matrix method.
In this part, you should solve the equation by both the methods and compare the solution.

Your application should accept the parameters, from the console, and construct the equations. For example, it should ask you to prompt for ‘a’, ‘b’ and ‘c’ and ‘p’, ‘q’ and ‘r’ to construct the equations.

ax+by=c,and

px+qy=r

When performing the computation using the matrix method, your application should indicate the intermediary results such as determinant, inverted matrix etc.

As you are aware, for any two given linear equations, when there is a solution, these two lines intersect. When there is no solution, these two lines don’t intersect, and, could be that they run parallel, for example.

 
#### Part 2:

When there is a solution, ie, when these two lines are intersecting, you should plot the lines using the characters on the console in the following format: This is a sample graph, not to scale and is not representing the given set of equations.

Your application should be able to demonstrate that it can handle any set of equations, and when there is a solution, it can plot a graph on the console, as above, else it will be able to let you know that there is no solution.

 
Assumptions
Students are aware of basic algebra and know the ways solutions are computed. Students are aware of using c, libraries, functions etc. to create the project.

 
Sample Data
The linear equations set having a solution:
3x + 2y – 7 = 0, and
5x – 3y – 37 = 0

 

The linear equations set having no solution (parallel lines):
3x -y +2 = 0
-3x +y = 0

 

Note:
Problem can be treated programmatically, by adopting 2 different solution methods: substitution method and matrix manipulation method (using matrix inversion, matrix multiplication and other functions).

In part 2, the graph is to be plotted.
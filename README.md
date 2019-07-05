# Maze-Solver-with-Shortest-Path-Algorithm
This robot travels through the maze using left hand rule and finds the end of it. Now, based on the directions it has recorded, Using the shortest path algorithm it travels in the shortest path when placed at the start of the maze avoiding wrong turns and dead-ends.\
**GETTING THE SHORTEST PATH**\
We search the element 'U' from the array and remove it. We get the shortest route from the completed path by using **"Replacement Rules"**\
**REPLACEMENT RULES**\
Replacement rules are used to find the shortest path in the given maze. This rule stores the turns taken during the maze solving phase and corrects all wrong turns taken by replacing particular strings. The optimun path can thus be found by applying replacement rules to the "Directions" Array.\
Here,\
S = Straight\
R = Right\
L = Left\
U = U-Turn\
Whenever the character 'U' appears on the Directions array when use **Replacement Rules.**
1. LUR = U
2. LUS = R
3. RUL = U
4. SUL = R
5. SUS = U
6. LUL = S \
We use the replaced Strings to make the robot take the Shortest Path.

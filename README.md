This Java program implements the A* search algorithm to solve the classic Missionaries and Cannibals problem. The problem involves transferring a group of missionaries and cannibals from one side of a river to the other using a boat, while ensuring that at no point do the cannibals outnumber the missionaries on either side.


Execution Flow
Initialization: The program starts by initializing the Astar class, which in turn initializes the start node with all missionaries and cannibals on the left bank and the boat also on the left bank.
A Search*: The solve() method iteratively explores nodes, generating successor states and adding them to the open list if they are valid and not already explored. The heuristic function guides the search by prioritizing nodes that are closer to the goal.
Solution: When the goal state (all missionaries and cannibals on the right bank) is reached, the search terminates, and the print() method outputs the sequence of moves leading to the solution.

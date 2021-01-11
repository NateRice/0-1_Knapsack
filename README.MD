# 0-1 Knapsack Problem _using branch and bound best first search method_
_An example of this problem concerns a thief breaking into a jewelry store carrying a knapsack. The 
knapsack will break if the total weight of the items stolen exceeds some maximum weight W. Each item 
has a value and a weight. The thief’s dilemma is to maximize the total value of the items while not 
making the total weight exceed W. This problem is called the 0-1 Knapsack problem
("Foundations of Algorithms"-Neapolitan)._

# Implementation
Implemented in Python. Optimal solution includes the maximum profit and a list of items that make the
maximum profit. Returns maxprofit value with list storing the index position of the items in the best
solution. The profit is maximized while staying under the weight limit. This program uses a priority 
queue to store the nodes ordered by best bound, the nodes are sorted as they are inserted into the 
priority queue. The node with the highest bound value is returned when removing from the priority queue.
The best first approach arrives at an optimal solition faster than breadth first search especially with
larger problem sets with a large amount of items.
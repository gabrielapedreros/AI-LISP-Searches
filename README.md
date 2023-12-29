# Tree Searches Problem
Implement several brute-force search algorithms. All programs must work for tree of arbitrary depth and branching factors. The search tree will be represented as lists where:
 -leaf node represents an atom
 -non-leaf node represents list of child nodes
Example: list ((W X) (Y Z)) represents a two-level binary tree 

# DFS - Depth-First Search
The function takes in a single argument that is a list representation of the tree. The function should return a single, top-level list of the terminal nodes in order from left-to-right depth-first search.
Example: (dfs '((A (B)) C (D))) would return (A B C D)

# DFID - Depth-First Iterative Deepening
The top-level function, DFID, takes in two arguments: the list representation of the tree and an integer representing the max depth of the tree. This function will return a single top-level list of the terminal nodes in the order that they would be visited by left-to-right depth-first iterative-deepening search. Nodes visited in multiple iterations will appear multiple times in the output.
Example: (dfid '((A (B)) C(D)) 3) would return (C A C D A B C D)

# BFS - Breadth First Search 
The function takes in a single argument that is the list representation of the tree. The function will return a single, top-level list of terminal nodes in order left-to-right breadth-first search.
Example: (bfs '((A (B)) C(D))) would return (C A D B)

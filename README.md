# A-star

A* (pronounced as "A star") is a computer algorithm that is widely used in pathfinding and graph traversal. The algorithm efficiently plots a walkable path between multiple nodes, or points, on the graph. 

A* works by making a lowest-cost path tree from the start node to the target node. What makes A* different and better for many searches is that for each node, A* uses a function f(n) that gives an estimate of the total cost of a path using that node. Therefore, A* is a heuristic function, which differs from an algorithm in that a heuristic is more of an estimate and is not necessarily provably correct. 

A* expands paths that are already less expensive by using this function: 

<div align="center">f(n) = g(n) + h(n)</div>

where

- *f(n)* = total estimated cost of path through node n.

- *g(n)* = cost so far to reach node n.

- *h(n)* = estimated cost from n to goal. This is the heuristic part of the cost function, so it is like a guess. 

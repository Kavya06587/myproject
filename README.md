
1. Best First Search (Greedy Search)

=>Approach: Expands the node that appears closest to the goal, using only the heuristic function h(n).
=>Optimality: Not guaranteed to find the shortest path, since it ignores the actual cost taken so far.
=>Efficiency: Usually faster and explores fewer nodes, but may lead to longer or incorrect paths.
=>Use case: When speed is more important than accuracy, or when an approximate solution is acceptable.

2. A* Search

=>Approach: Expands nodes based on f(n) = g(n) + h(n), where g(n) is the cost so far and h(n) is the estimated cost to the goal.
=>Optimality: Guarantees the shortest (optimal) path if the heuristic is admissible (never overestimates).
=>Efficiency: Slower than Best First Search because it considers both path cost and heuristic, often exploring more nodes.
=>Use case: When accuracy and finding the optimal path are critical, such as in routing, AI planning, or navigation.

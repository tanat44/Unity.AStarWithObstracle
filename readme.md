# Unity.AStarWithObstacle

A* path finding implemented in Unity
- The A* search algorithm is based on pseudo code in [wikipedia](https://en.wikipedia.org/wiki/A*_search_algorithm)
- Priority queue implementation is taken from [stack overflow](https://github.com/FyiurAmron/PriorityQueue/blob/main/PriorityQueue.cs)
- 2D obstacle map is built using 2D array based on Unity's Bounds of the ***Pink GameObjects***.
- Starting point is ***Yellow*** and Goal is ***Green***
- Green path is the solution. Path is only visualized in the Editor's Scene window.

![Result](/docs/screenshot.png)
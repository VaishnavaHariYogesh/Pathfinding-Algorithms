# Pathfinding Algorithms for Autonomous Navigation

An in-progress Python honors project for Data Structures. The goal is to build a grid-based simulator and compare how Breadth-First Search (BFS), Dijkstra's algorithm, and A* find a route from a start point to a destination while avoiding obstacles.

## Status

**Planning / early development.** This README describes the project goal and planned work. Algorithm implementations and comparison results will be added as they are completed.

## Why this project?

Navigation is a practical way to see data structures in action. The project will use graphs, queues, priority queues, sets, and dictionaries, then show how algorithm choices affect the route and the number of grid cells explored. The grid is a simplified model for learning about autonomous navigation, not a vehicle navigation system.

## Planned features

- Define grids with a start, destination, and obstacles.
- Implement BFS, Dijkstra's algorithm, and A*.
- Show the route each algorithm finds and the cells it checks.
- Run the same algorithms on at least three maps.
- Compare path length, explored cells, and, if measured consistently, execution time.
- Summarize the results in a short report and presentation.

## Technologies

- Python
- Python data structures such as queues, priority queues, sets, and dictionaries

## How to run

Run instructions will be added when the first working version is available.

## Project roadmap

1. Design the grid representation and implement BFS.
2. Add Dijkstra's algorithm and A*.
3. Display explored cells and the final path.
4. Test at least three maps and record comparable results.
5. Explain the differences and add results, examples, and setup instructions here.

## Notes on the comparison

The algorithms need to use the same map and movement rules for each test. If all moves have equal cost, BFS and Dijkstra's algorithm may return paths of the same length; differences in explored cells and runtime can still be useful to study. The assumptions and test setup will be documented alongside the results.

## Academic context

Developed as an IU Indianapolis Data Structures honors project. The planned deliverables include the program, tests on at least three maps, a written report, and a short presentation.

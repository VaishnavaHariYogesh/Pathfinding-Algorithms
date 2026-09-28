# Pathfinding Algorithms for Autonomous Navigation

**Status: Planned — implementation has not started.**

This Data Structures honors project will compare three pathfinding algorithms in Python: breadth-first search (BFS), Dijkstra's algorithm, and A*. The program will use a grid with a start, destination, and obstacles. I will examine the paths each algorithm finds and how much of the grid it explores.

## Project question

How do BFS, Dijkstra's algorithm, and A* differ when solving the same navigation problem?

I chose this project to apply graphs, queues, priority queues, sets, and dictionaries to a concrete problem related to autonomous navigation. A grid is a simplified learning model, not a real vehicle navigation system.

## Planned comparison

Each algorithm will run on the same maps and follow the same movement rules. I plan to compare:

- Whether it finds a path and the length or cost of that path.
- How many grid cells it explores.
- Execution time, if the tests are set up consistently enough for a useful comparison.

I will test at least three maps with different obstacle layouts. If every move has the same cost, BFS and Dijkstra's algorithm may find paths of equal length; I will still compare their search behavior.

## Build milestones

- [ ] Design a grid with start, destination, and obstacles.
- [ ] Implement and verify BFS.
- [ ] Implement Dijkstra's algorithm and A*.
- [ ] Display explored cells and the final path.
- [ ] Test at least three maps and record comparable results.
- [ ] Add findings, example output, and instructions for running the program.

## Current repository contents

This README documents the scope and implementation plan. There is no runnable program yet. As I complete milestones, I will add the code and update this page with actual results and setup instructions.

## Academic context

IU Indianapolis Data Structures honors project. The planned final work includes a Python program, a comparison across at least three maps, a written report, and a presentation.

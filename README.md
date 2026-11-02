# route_finder|
# Campus Route Finder Using Graphs

**Student Name:** Bhawna  
**Project:** DSA Mini Project  
**Programming Language:** C

## 1. Introduction

Campus Route Finder is a simple C language project that helps users find routes between different campus locations using Graph Data Structures.

In this project, campus locations are represented as vertices and paths between them are represented as edges.

## 2. Campus Locations

The project includes the following 8 locations:

| Number | Location |
|---|---|
| 0 | Main Gate |
| 1 | Library |
| 2 | Block 1 |
| 3 | Block 2 |
| 4 | Cafeteria |
| 5 | Auditorium |
| 6 | Parking |
| 7 | Lab |

## 3. Features

- Displays all campus locations.
- Finds the shortest route using Breadth-First Search (BFS).
- Displays reachable locations using Depth-First Search (DFS).
- Identifies disconnected locations.
- Provides a simple menu-driven interface.
- Handles invalid location numbers.

## 4. Data Structures and Algorithms Used

- Graph
- Adjacency List
- Breadth-First Search (BFS)
- Depth-First Search (DFS)
- Queue
- Linked List
- Visited Array
- Parent Array

## 5. Time Complexity

| Algorithm | Time Complexity |
|---|---|
| BFS | O(V + E) |
| DFS | O(V + E) |

Where V represents vertices and E represents edges.

## 6. How to Run the Project

**Step 1:** Download or clone this repository.

**Step 2:** Open the project folder in Dev-C++, Code::Blocks or VS Code.

**Step 3:** Compile the program using GCC:

```bash
gcc main.c -o campus
```

**Step 4:** Run the program:

```bash
campus
```

On Windows, run `campus.exe`.

## 7. Test Cases

1. Display all campus locations.
2. Find a shortest route from Main Gate to Auditorium.
3. Display reachable locations using DFS.
4. Enter an invalid location number and check the error message.

## 8. Project Files

- `main.c` – C source code.
- `Report.pdf` – Project report.
- `test_cases.txt` – Test cases.
- `sample_output.txt` – Sample program output.
- `screenshots/` – Program output screenshots.

## 9. Conclusion

This project demonstrates the practical application of graphs in route finding. It uses BFS to find the shortest route and DFS to explore reachable campus locations. It also helps understand graph representation and traversal algorithms in C.

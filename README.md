
````markdown
# Dynamic Pathfinding Agent

## Project Overview
Dynamic Pathfinding Agent is a Python-based interactive visualization tool that demonstrates pathfinding algorithms on a grid environment. 

The project allows users to:
- Place walls (obstacles)
- Choose between A* and Greedy Best-First Search (GBFS)
- Toggle between Manhattan and Euclidean heuristics
- View live metrics such as nodes visited, path cost, and execution time

This project helps in understanding how informed search algorithms work in Artificial Intelligence.

---

## Features
- Interactive grid visualization using Pygame
- A* Search Algorithm (Optimal)
- Greedy Best-First Search (Fast but not optimal)
- Manhattan and Euclidean heuristics
- Real-time search animation
- Performance metrics display
- Random wall generation
- Adjustable grid size

---

## Technologies Used
- Python 3
- Pygame
- PriorityQueue (for open set management)

---

## Installation

Make sure Python 3 is installed.

Install required dependency:

```bash
pip install pygame
````

---

## How to Run

Navigate to the project folder and run:

```bash
python pathfinding.py
```

You will be asked to enter grid size (e.g., 25).

---

## Controls

| Key / Action     | Function                                 |
| ---------------- | ---------------------------------------- |
| Left Mouse Click | Place wall                               |
| SPACE            | Start search                             |
| R                | Reset grid                               |
| M                | Generate random walls                    |
| 1                | Select A* algorithm                      |
| 2                | Select GBFS algorithm                    |
| H                | Toggle heuristic (Manhattan ↔ Euclidean) |
| Close Window     | Exit program                             |

---

## Algorithms Implemented

### A* Algorithm

* Uses f(n) = g(n) + h(n)
* Guarantees shortest path (if heuristic is admissible)

### Greedy Best-First Search (GBFS)

* Uses only h(n)
* Faster but does not guarantee optimal path

---

## Metrics Displayed

* Algorithm used
* Heuristic type
* Nodes visited
* Path cost
* Execution time (ms)

---

## Learning Outcome

This project demonstrates:

* Heuristic search techniques
* Priority Queue usage
* Graph traversal concepts
* Real-time visualization with Pygame

---

## (Optional) Screenshots

You can add screenshots of your program here.

---

## Author

Your Name
BS Computer Science

```

---

# Why This Is Good?

✔ Looks professional  
✔ Covers installation instructions (important for grading)  
✔ Explains algorithms clearly  
✔ Includes controls  
✔ Shows learning outcome  




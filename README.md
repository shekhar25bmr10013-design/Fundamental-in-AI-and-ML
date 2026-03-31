# Fundamental-in-AI-and-ML
AI-based robot navigation system using the A* search algorithm to find the shortest path in a 2D obstacle-filled room.

#  A* Robot Navigation System

An AI-based pathfinding project that has a robot moving inside a 2D room with obstacles using the **A* (A-star) search algorithm**.

---

##  Project Overview
The objective of this project is to help a robot move from a **start position** to a **goal position** while avoiding obstacles such as walls, furniture, or blocked areas.

The system uses the **A* algorithm** to compute the shortest collision-free path.

This simulates real-world applications such as:
- warehouse robots
- robotic vacuum cleaners
- autonomous indoor delivery bots
- game pathfinding systems

---

##  Algorithm Used
The project uses the **A* Search Algorithm**, one of the most efficient pathfinding algorithms in Artificial Intelligence.

Formula used:

f(n) = g(n) + h(n)

Where:
- **g(n)** = actual distance travelled from start node
- **h(n)** = estimated distance to goal node (heuristic)
- **f(n)** = total estimated cost

The heuristic used in this project is **Manhattan Distance**.

---

##  Features

- 2D room/grid simulation
- static obstacle placement
- shortest path calculation
- visual path display
- start and destination nodes
- AI-based decision making
- 
---

##  How to Run the Project
### 1. Install Dependencies
```bash
pip install pygame
```

### 2. Run the Program
```bash
python main.py
```

---

##  Output
The output window displays:
- **green cell** → robot start position
- **red cell** → target destination
- **black cells** → obstacles
- **blue cells** → shortest path found

---

##  Learning Outcomes
This project helped in understanding:
- AI search algorithms
- heuristic functions
- shortest path optimization
- robotics-based problem solving

---

## 👨‍💻 Author
BYOP Project for **Fundamentals of AI and ML**

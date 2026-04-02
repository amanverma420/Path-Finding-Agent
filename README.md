Here’s a clean and professional `README.md` for your project based on the provided code :

---

# 🤖 AI Pathfinding Agent — Dynamic 2D Grid

**Author:** Aman Verma
**MIS:** 612303196
**Institution:** COEP Technological University
**Department:** Computer Science & Engineering

---

## 📌 Overview

This project is an **interactive AI Pathfinding Visualizer** built using **HTML, CSS, and JavaScript**. It demonstrates how different search algorithms navigate a dynamic 2D grid with obstacles to reach a goal.

The system simulates an intelligent agent that finds paths using classical AI search techniques, while providing **real-time visualization, statistics, and heatmaps**.

---

## 🚀 Features

* 🎯 **5 Search Algorithms Implemented**

  * A* (A-Star)
  * Breadth-First Search (BFS)
  * Depth-First Search (DFS)
  * Uniform Cost Search (UCS)
  * Greedy Best-First Search

* 🧠 **Dynamic Grid Environment**

  * 25 × 25 grid
  * 30% randomly generated obstacles
  * Guaranteed reachable goal (connectivity ensured)

* 🎮 **Interactive Controls**

  * Set **Start** and **Goal** by clicking
  * Start / Pause / Reset simulation
  * Adjustable animation speed

* 📊 **Live Statistics**

  * Steps taken
  * Nodes explored
  * Cells visited
  * Optimal path length

* 🔥 **Heatmap Visualization**

  * Shows how frequently cells are visited

* 🧾 **Event Logging**

  * Real-time logs of algorithm behavior

---

## 🧮 Algorithms Explained

| Algorithm  | Optimal | Complete | Notes                                           |
| ---------- | ------- | -------- | ----------------------------------------------- |
| **A***     | ✅ Yes   | ✅ Yes    | Uses `f(n) = g(n) + h(n)` (Manhattan heuristic) |
| **BFS**    | ✅ Yes   | ✅ Yes    | Guarantees shortest path (uniform cost)         |
| **DFS**    | ❌ No    | ✅ Yes    | May take longer/non-optimal paths               |
| **UCS**    | ✅ Yes   | ✅ Yes    | Same as BFS in this grid (cost = 1)             |
| **Greedy** | ❌ No    | ✅ Yes    | Fast but not optimal                            |

---

## 🛠️ How It Works

1. The grid is initialized with random obstacles.
2. The user selects:

   * Algorithm
   * Start position
   * Goal position
3. The agent moves step-by-step:

   * Recomputes path dynamically
   * Updates visited cells and stats
4. Once the goal is reached:

   * Optimal path is computed (via A*)
   * Displayed in **green**

---

## ▶️ How to Run

### Option 1: Directly in Browser

1. Download the project file
2. Open the HTML file in any browser:

   ```
   double-click → open in Chrome/Edge
   ```

### Option 2: Live Server (Recommended)

```bash
# If using VS Code
Right-click → Open with Live Server
```

---

## 🎯 Controls Guide

* 🖱️ Click grid:

  * First click → Set **Start**
  * Second click → Set **Goal**
* ▶️ Start Simulation
* ⏸ Pause / Resume
* ↺ Reset Grid
* 🎚 Adjust speed slider

---

## 🎨 Legend

| Color     | Meaning                   |
| --------- | ------------------------- |
| ⚪ White   | Free cell                 |
| ⚫ Dark    | Obstacle                  |
| 🔵 Blue   | Start                     |
| 🟠 Orange | Goal                      |
| 🟣 Purple | Agent                     |
| 🟢 Green  | Optimal Path              |
| 🔴 Shades | Heatmap (visit frequency) |

---

## 📈 Key Concepts Demonstrated

* Heuristic search (A*)
* Graph traversal
* State space exploration
* Trade-offs between optimality and speed
* Real-time simulation systems

---

## 📂 Project Structure

```
project/
│
├── index.html   # Main application (UI + logic)
└── README.md    # Documentation
```

---

## 💡 Future Improvements

* Diagonal movement support
* Weighted grids
* Custom obstacle drawing
* Additional heuristics (Euclidean, Chebyshev)
* Algorithm comparison mode

---

## 🏁 Conclusion

This project provides a **visual and intuitive understanding of AI search algorithms**, making it ideal for:

* Students learning AI & DSA
* Demonstrations in labs
* Algorithm comparison studies

---

## ⭐ Acknowledgement

Developed as part of **AI Lab Assignment** at COEP Technological University.

---
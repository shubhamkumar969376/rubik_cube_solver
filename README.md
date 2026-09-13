# 🧩 Rubik's Cube Solver

A **Rubik's Cube Solver** implemented using programming and algorithmic techniques to find a sequence of moves that transforms a scrambled cube into its solved state.

The project focuses on representing the Rubik's Cube efficiently, performing cube rotations, and searching for a valid solution.

---

## 🚀 Features

* 🧩 Digital representation of a Rubik's Cube
* 🔄 Supports standard cube rotations
* 🎯 Checks whether the cube is solved
* 🔍 Searches for a sequence of moves to solve the cube
* ⚡ Uses algorithmic search techniques to explore possible cube states
* 🧠 Demonstrates practical applications of **Data Structures and Algorithms**

---

## 🧠 How It Works

The solver can be understood in three main stages:

```text
             Scrambled Cube
                    │
                    ▼
          Cube State Representation
                    │
                    ▼
          Generate Possible Moves
                    │
                    ▼
            Search Cube States
                    │
                    ▼
          Find Solution Sequence
                    │
                    ▼
             Solved Cube 🧩
```

### 1. Cube Representation

The cube is represented programmatically so that each face and its individual pieces can be tracked after every rotation.

### 2. Move Generation

The program generates valid Rubik's Cube moves and updates the cube state after each move.

Examples of standard moves include:

```text
U   → Upper face
D   → Down face
L   → Left face
R   → Right face
F   → Front face
B   → Back face
```

Prime moves represent counter-clockwise rotations:

```text
U'
D'
L'
R'
F'
B'
```

---

## 🔎 Solving Approach

The solver explores different possible cube configurations starting from the scrambled state.

Each configuration can be considered as a **state**, while each valid cube rotation represents an **edge between states**.

```text
        State A
       /      \
      /        \
   Move 1     Move 2
    /            \
State B        State C
    \            /
     \          /
       Solved
```

The goal is to find a sequence of moves that reaches the solved configuration.

This project provides practical understanding of:

* State-space search
* Graph traversal
* Backtracking
* Hashing / state tracking
* Time and space complexity
* Algorithm optimization

---

## 🛠️ Concepts Used

### Data Structures

* Arrays / Vectors
* Strings
* Sets / Hashing
* Queues / Search structures

### Algorithms

* State-space search
* Backtracking
* Graph traversal
* Duplicate-state detection

### Programming Concepts

* Object-oriented programming
* State representation
* Modular design
* Algorithm optimization

---

## 📂 Project Structure

```text
rubik_cube_solver/
│
├── rubiks-cube-solver-main/
│   ├── ...
│   └── ...
│
└── README.md
```

---

## ▶️ Getting Started

### Clone the Repository

```bash
git clone https://github.com/shubhamkumar969376/rubik_cube_solver.git
```

```bash
cd rubik_cube_solver
```

### Run the Project

Follow the instructions according to the source files inside:

```text
rubiks-cube-solver-main/
```

---

## 🎯 Learning Objectives

This project was built to understand how complex real-world problems can be represented as a **state-space search problem**.

The main learning objectives are:

* Understanding state representation
* Designing efficient cube operations
* Generating valid transitions
* Searching through a large state space
* Avoiding repeated states
* Finding an efficient path to the solved state

---

## 🔮 Future Improvements

* [ ] Add an interactive GUI
* [ ] Add 3D visualization of the cube
* [ ] Display the solution moves step-by-step
* [ ] Add multiple solving algorithms
* [ ] Improve search performance
* [ ] Add optimal-solution support
* [ ] Add scramble generator
* [ ] Add move counter
* [ ] Add cube-state validation
* [ ] Deploy as a web application

---

## 📸 Demo

> Add screenshots or a GIF of the solver here.

```text
Scrambled Cube
      ↓
Solution Found
      ↓
Solved Cube
```

---

## 📚 What I Learned

Through this project, I explored how a Rubik's Cube can be modeled as a computational state-space problem.

The project helped strengthen my understanding of:

**Data Structures → Algorithms → State Representation → Search → Optimization**

---

## 👨‍💻 Author

**Shubham Kumar**

GitHub: [@shubhamkumar969376](https://github.com/shubhamkumar969376)

---

## ⭐ Support

If you find this project interesting, consider giving the repository a ⭐.

Suggestions and contributions are welcome!

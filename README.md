# Automata and Language Theory | Simulation & Visualization Tool

An interactive educational and research tool built to let users easily simulate, test, and visualize abstract computational models like finite automata, grammars, and tape-based machines through clear step-by-step graphical animations.

Built as a CST4 final project by Bai Fatima Andong, Fionnah Keiz Coyoca, Christian James Cahilig, Karylle Mish Gellica, and John Llorie Sarmiento, University of Mindanao.

---

## What This Does

This application breaks down the abstract rules of formal language theory into clear, real-time visual step-logs. 

Instead of guessing how a machine processes a string or handles transitions, you can input strings directly and watch the graphical interface step through state changes, character pushes or pops, and tape head movements. It acts as an interactive simulator designed to make theory-heavy computer science concepts easy to look at and understand.

---

## Core Models Simulated

The tool features six distinct computational and mathematical model simulations:

- **DFA & NFA:** Watch state transitions highlight in real time as characters are read from an input string.
- **Pushdown Automata (PDA):** Visualizes character stack activity, showing exact push and pop operations during processing.
- **Context-Free Grammars (CFG):** Steps through string derivation trees and grammar production rules.
- **Turing Machine:** Animates tape-head pointer movements doing binary addition and unary multiplication.
- **Tower of Hanoi:** Visualizes state space tree traversal and recursive disk shifting step-by-step.

---

## Features

- **Live Animation Controls:** Pause, play, or step through state machine transitions at your own pace
- **Trace-Logged Debugging:** A real-time side log that displays the exact execution paths and variables
- **Input Cap Safeguards:** Built-in limits on maximum input values to ensure smooth graphical rendering
- **Interactive UI Forms:** Simple clean menus to switch models and key in test cases instantly

---

## Installing and Running Locally

Follow these steps to run the project on your own computer.

### What You'll Need First

Make sure you have these installed before starting:

- **Java Development Kit (JDK 17 or higher)** — Download from [oracle.com](https://www.oracle.com/java/technologies/downloads/).
- **Git** — Download from [git-scm.com](https://git-scm.com/downloads).

To check if they're ready, open a terminal (Command Prompt on Windows, Terminal on Mac/Linux) and type:

java -version
git --version

---

### Step 1 — Clone the Repository

This downloads a copy of the project to your computer:

git clone https://github.com/mishgellica/automata-language-theory.git
cd automata-language-theory

---

### Step 2 — Compile the Code

Compile all Java source files from your command terminal:

javac src/*.java


---

### Step 3 — Run the App

Launch the application window using the main execution layer:

java src/Main


*(Note: Replace `Main` with the specific entry point filename if your project structure uses a different driver class).*

---

## Tech Stack

- **Interface Framework:** Java Swing (GUI Graphics & Timers)
- **Execution Engine:** Java Development Kit (JDK)
- **Architecture Layout:** Object-Oriented Simulation Logic

---

## Limitations

- **Desktop Bound Application:** Runs as a native desktop layout window rather than a live website link or hosted browser application.
- **Performance Boundary Caps:** Heavy string inputs or massive recursion depths are limited by maximum value guards to prevent interface lagging.

---

## Authors

* **Bai Fatima A. Andong** — b.andong.545438@umindanao.edu.ph
* **Fionnah Keiz Coyoca** — f.coyoca.544111@umindanao.edu.ph
* **Christian James C. Cahilig** — c.cahilig.544797@umindanao.edu.ph
* **Karylle Mish T. Gellica** — k.gellica.544337@umindanao.edu.ph
* **John Llorie Sarmiento** — j.sarmiento.545495@umindanao.edu.ph

BS Computer Science, University of Mindanao — CST4 Final Project, 2026

---

## License

This project is for academic and educational purposes only.

# operating_system
simulation of concepts of os

# 🖥️ Memory Management Simulator

This project is a **GUI-based Memory Management Simulator** built with Python’s `Tkinter`.
It simulates how an **Operating System manages memory** using allocation, deallocation, swapping, and compaction.

---

## 🚀 Features

Add Process: Allocates memory to a process using **First-Fit strategy**.
Remove Process: Deallocates memory of the selected process.
Swap Out: Removes the earliest allocated process (like FIFO page replacement).
Compact Memory: Eliminates fragmentation by shifting processes upward.
Merge Holes: Combines adjacent free blocks into larger holes.
Visualization:

  * Green blocks → allocated processes
  * Red blocks → free memory holes
  * Memory usage stats shown at the bottom
* Event Log*: Displays all memory events (allocation, removal, compaction, etc.).

---

## 📸 Screenshot (example)



---

## ⚙️ How It Works

Memory is represented as a block of `100 MB`.
Processes are given a unique ID (P1, P2, …) and allocated memory from free blocks.
If memory is fragmented, the user can **compact** to rearrange processes.
The system supports **basic memory management operations** found in Operating Systems.

---

## 📚 Concepts Demonstrated

This project helps visualize the following OS concepts:

Contiguous Memory Allocation
First-Fit Allocation Strategy
Internal & External Fragmentation
Compaction
Swapping

---

## 🛠️ Tech Stack

Python 3
Tkinter (for GUI)

---

## ▶️ How to Run

1. Clone or download the project.
2. Make sure Python 3 is installed:

   ```bash
   python --version
   ```
3. Run the simulator:

   ```bash
   python memory_simulator.py
   ```

---

## ✨ Future Improvements

* Add **Best-Fit** and **Worst-Fit** allocation strategies.
* Show **fragmentation statistics**.
* Add **swap-in** functionality.
* Use unique colors per process for better visualization.



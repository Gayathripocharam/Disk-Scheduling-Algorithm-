# Disk Scheduling Algorithm Visualizer

A modern, interactive Python application for visualizing common Operating System Disk Scheduling Algorithms. Built with `customtkinter` for a sleek dark mode interface and `matplotlib` for generating insightful performance graphs.

## 🧠 Why This Project Matters
- **Demonstrates OS-level scheduling concepts**
- **Visualizes algorithm efficiency**
- **Bridges theory + practical implementation**

## 📌 Features
- **FCFS, SSTF, SCAN, C-SCAN** support
- **Dynamic best algorithm selection**
- **Real-time visualization**
- **Seek time calculation**

## 📊 Algorithms Included
- **FCFS** → Simple, no optimization
- **SSTF** → Minimizes seek time
- **SCAN** → Elevator algorithm
- **C-SCAN** → Circular scan (better fairness)

## 📈 Time Complexity
| Algorithm | Complexity |
|-----------|------------|
| FCFS | O(n) |
| SSTF | O(n²) |
| SCAN | O(n log n) |
| C-SCAN | O(n log n) |

## How to Run

1. Clone the repository and navigate into the folder:
   ```bash
   git clone https://github.com/Gayathripocharam/disk-scheduling-visualizer.git
   cd disk-scheduling-visualizer
   ```

2. Install the necessary Python packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the GUI:
   ```bash
   python disk_scheduling_gui.py
   ```

## Requirements
- Python 3.8+
- matplotlib
- customtkinter

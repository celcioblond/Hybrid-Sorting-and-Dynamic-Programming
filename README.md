# 🧠 Hybrid Sorting and Dynamic Programming Optimization

This project explores two key topics in algorithm design and analysis:
1. **Hybrid Sorting Algorithms** (C++ + Python)
2. **Dynamic Programming Optimization (0/1 Knapsack Problem)**

---

## 📘 Overview

- **Part 1:** Implements and analyzes a **Hybrid Sort** combining Merge Sort and Insertion Sort.  
  The project tests how the threshold value `K` affects performance for different input sizes (`n`) and data types (random vs pre-sorted arrays).  

- **Part 2:** Implements a **Dynamic Programming** solution to the 0/1 Knapsack Problem, maximizing “enjoyment points” under weight constraints.

The project demonstrates the trade-off between **divide-and-conquer efficiency** and **in-place sorting simplicity**, and showcases how **empirical data analysis** can optimize algorithm parameters.

---

## 🧩 Technologies Used
- **C++** → For implementing and benchmarking sorting algorithms  
- **Python (Pandas, Matplotlib)** → For data visualization and analysis  
- **Java** → For solving the Knapsack Problem via Dynamic Programming  

---

## 🧪 How to Run

### **1. Compile the C++ Programs**
```bash
# Random array
g++ hybridSortRandom.cpp -o hybridSort
./hybridSort

# Sorted array
g++ sorted.cpp -o sorted
./sorted

### Each program will generate
output.csv (for random arrays)
output_sorted.csv (for sorted arrays)

### **2. Generate Graphs with Python
# Random array
cd "Random array"
python graph.py
python graphOptimalK.py

# Sorted array
cd "../sorted array"
python graph.py
python graphOptimalK.py

## 🎯 Purpose
This project demonstrates how **algorithmic design choices** affect performance and efficiency in practical applications.  
It emphasizes:
- Analytical reasoning  
- Empirical performance analysis  
- Optimization through data-driven insights

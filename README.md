# Real-Time Memory Allocation Tracker

## 📘 Project Overview

**Real-Time Memory Allocation Tracker (RTMAT)** is a C-based system utility designed to monitor, track, and optimize memory usage dynamically in real time. Developed as part of the CSE316 Operating Systems course at Lovely Professional University, this project helps identify memory allocation patterns, memory leaks, fragmentation, and overall memory management efficiency in operating systems.

---

## 👨‍💻 Authors

- **P. Mahammad Yaseen** (Reg No: 12317975)
- **P. Surendra**
- **M. Manasvi**

Supervised by: **Dr. Parvinder Singh**  
Department: **Computer Science and Engineering, Lovely Professional University**

---

## 🔍 Features

- Real-time tracking of memory usage.
- Visualization of allocated, available, and used memory.
- Simulation of paging and segmentation techniques.
- Detection of memory leaks and fragmentation.
- Minimal overhead to maintain real-time system performance.
- Optional GUI or web-based dashboard support.

---

## 🛠️ System Requirements

### Hardware
- **Minimum**: Intel i5, 8GB RAM, 256GB SSD
- **Recommended**: Intel i7/i9 or Ryzen 7/9, 16GB+ RAM, 512GB SSD

### Software
- OS: Linux (preferred), Windows 10/11, macOS
- Languages: C/C++, Python (optional for visualization)
- Tools: `gcc`, `Valgrind`, `AddressSanitizer`, `Matplotlib/Grafana`

---

## ⚙️ Installation & Execution

### Compile:
```bash
gcc -o memory_tracker memory_tracker.c

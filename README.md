# Moth-Flame Optimization (MFO) Implementation

This repository contains a Python implementation of the **Moth-Flame Optimization (MFO)** algorithm, a nature-inspired heuristic search algorithm based on the navigation method of moths in nature.

The script tests the algorithm's performance on two classic benchmark functions:
1. **Sphere Function** (Unimodal)
2. **Rastrigin Function** (Multimodal)

## 💡 How it Works
Moths use a transverse orientation for navigation. In this algorithm, moths are the search agents, and flames are the best positions obtained so far. Moths update their positions using a logarithmic spiral around a flame.



## 🛠️ Requirements
To run this project, you need Python installed along with the following libraries:
* `numpy`
* `matplotlib`

You can install them via pip:
```bash
pip install numpy matplotlib

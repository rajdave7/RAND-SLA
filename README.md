# RAND-SLA: A Randomized Skeleton Learning Algorithm for Bayesian Structure Learning

This repository contains the implementation of **RAND-SLA**, a novel algorithm designed to enhance Bayesian structure learning by addressing the challenges of traditional skeleton learning methods. RAND-SLA reduces complexity, improves scalability, and achieves efficient probabilistic inference for large graphs.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Contributors](#contributors)

---

## Introduction

Bayesian Networks are graphical models that represent probabilistic relationships among variables using Directed Acyclic Graphs (DAGs). The process of learning these networks typically involves:
1. Identifying the skeleton.
2. Detecting immoralities and orienting edges.
3. Orienting additional edges incident on colliders.

**RAND-SLA** optimizes this process by adopting a randomized approach, which eliminates the dependency on the number of neighbors (N) and reduces computational complexity.

---

## Features

1. **Reduction in Complexity**:
   - RAND-SLA ensures linear growth in the number of tests compared to exponential growth in traditional iterative approaches.

2. **Scalability**:
   - Suitable for large-scale graphs, offering higher efficiency without compromising accuracy.

3. **Probabilistic Guarantees**:
   - The algorithm provides a robust method for finding valid conditioning sets and ensuring overall success rates.

---
## Results
The RAND-SLA algorithm outperforms traditional iterative skeleton learning approaches in:

-Execution Time: Reduced computational overhead.
-Scalability: Handles large datasets with ease.
-Accuracy: Maintains competitive performance in identifying conditional dependencies.

## Contributors
-Ayush Patel
-Kunj Kanzariya
-Preet Patel
-Raj Dave
-Rutul Patel
This project was developed as part of the course CSE516: Probabilistic Graphical Models under the guidance of Professor Dhaval Patel.

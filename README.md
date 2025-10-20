# bachelors-thesis
physics-informed neural networks


# Physics-Informed Neural Networks and their Applications

Final project for the Building AI course (and finishing my degree...)

## Summary

This project studies Physics-Informed Neural Networks (PINNs), a class of neural networks that incorporate physical laws into learning. It explores theoretical foundations, practical applications, and demonstrates implementation using Python.

## Background

PINNs address the challenge of solving forward and inverse problems governed by partial differential equations (PDEs). Traditional numerical methods can be computationally expensive or require simplifying assumptions. This topic is important because it bridges AI and physics, enabling efficient and flexible solutions for complex scientific problems.

This project focuses on:
* Understanding the principles of neural networks and PINNs
* Comparing PINNs with traditional numerical methods
* Exploring applications in physics and engineering
* Demonstrating forward and inverse problem solving through Python implementations

## How is it used?

The process involves:
1. Selecting representative problems governed by PDEs
2. Implementing PINNs in Python
3. Training networks using data and physics constraints
4. Analyzing results and comparing with traditional methods

Users include researchers, engineers, and students who need efficient solutions to PDE-based problems. PINNs are especially useful when experimental or simulated data is limited or noisy.


## Data sources and AI methods

No external datasets are used; simulations of PDEs provide the data. AI methods include:
* Neural networks
* Physics-informed loss functions
* Forward and inverse problem solving

Key references:
* [Physics-informed neural networks: A deep learning framework for solving forward and inverse problems involving nonlinear PDEs](https://www.sciencedirect.com/science/article/abs/pii/S0021999118307125) – Raissi et al.
* [Physics-Informed Neural Networks for Solving Forward and Inverse PDEs](https://arxiv.org/abs/2502.19843) – Baty
* [A hands-on introduction to Physics-Informed Neural Networks](https://arxiv.org/abs/2403.00599) – Baty
* [Scientific Machine Learning Through Physics–Informed Neural Networks](https://link.springer.com/article/10.1007/s10915-022-01939-z) – Cuomo et al.
* [A comprehensive analysis of PINNs: Variants, Applications, and Challenges](https://arxiv.org/abs/2505.22761) – Ajithkumar et al.

## Challenges

Limitations of PINNs include:
* Computational cost for high-dimensional problems
* Difficulty in selecting hyperparameters
* Sensitivity to noisy or sparse data
* Comparison with classical methods may reveal trade-offs in accuracy and efficiency

Ethical considerations:
* Ensuring reproducibility of scientific results
* Avoiding misuse in applications with safety-critical consequences

## What next?

Potential extensions:
* Explore hybrid methods combining PINNs with traditional numerical solvers
* Optimize network architectures for faster training
* Apply PINNs to more complex or real-world PDE problems
* Develop user-friendly Python packages or educational tutorials

## Acknowledgments

* Original research papers and tutorials on PINNs (see references above)
* Open source Python frameworks (PyTorch)

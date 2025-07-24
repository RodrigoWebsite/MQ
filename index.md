---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: single
title: "Modeling Entangled Qubits for Distributed Data Representation in Machine Learning"
author_profile: true
---

### **Project Idea**

Design and simulate a quantum neural network (QNN) that leverages **quantum entanglement** to model correlations in distributed datasets. My goal is to explore how entangled qubits can enhance representational capacity and learning performance in machine learning tasks.

---

## Background & Motivation

Quantum computing enables new computational models using **qubits**, which exist in a superposition and can become **entangled**, forming non-classical correlations. Machine learning, on the other hand, seeks to identify patterns in data. By combining these domains, **Quantum Neural Networks (QNNs)** may outperform classical models in certain settings by leveraging entanglement to encode richer relationships across inputs.

This project is motivated by a desire to:

- Explore how entanglement can code dependencies across distributed features.
- Simulate and analyze QNNs to observe how quantum effects influence learning.
- Bridge quantum theory with practical ML (machine learning) techniques.

---

## Resource Video (Basics of Neural Networks)

<br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/rEDzUT3ymw4?si=UJNqqWpieu4aCPP1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<br>

Now that you've seen how classical neural networks function, consider this question:

**What if information could be shared instantaneously between neurons, no matter how far apart they are in the network?**

In the quantum world, entanglement allows particles to be correlated in a way that has no classical equivalent.

Could a basic QNN leverage entanglement to represent non-local correlations between data points in a way that a classical neural network can't?

This project aims to explore that question through a digital simulation framework (which will be introduced in the tools section).

---

## References

- Kwak, Y., Yun, W. J., Jung, S., & Kim, J. (2021). *Quantum Neural Networks: Concepts, Applications, and Challenges*. [arXiv:2108.01468](https://arxiv.org/abs/2108.01468)
- Mitarai, K., Negoro, M., Kitagawa, M., & Fujii, K. (2018). *Quantum Circuit Learning*. [arXiv:1803.00745](https://arxiv.org/abs/1803.00745)
- Broughton, M., Verdon, G., McCourt, T., Martinez, A. J., Yoo, J. H., Isakov, S. V., ... & Mohseni, M. (2020). *TensorFlow Quantum: A Software Framework for Quantum Machine Learning*. [arXiv:2003.02989](https://arxiv.org/abs/2003.02989)

---

## Tools & Techniques

### Mathematics:
-  **Linear Algebra** - tensor products, unitary matrices, eigen states (model quantum gates, represent multiqubit-systems, and explore state evolution & measurement).
-  **Complex numbers** - amplitudes (encode probabilities) and phase representation (affects interference and entanglement).
-  **Probability Theory** - Born rule for measurement probabilities ( `|α|² + |β|² = 1`).
-   **Optimization** - (classical) gradient-based methods applied to PQCs (to train the basic QNN by minimizing a cost function)

### Quantum/CS Tools: 
- [Qiskit](https://qiskit.org/) – for quantum circuit simulation and visualization
- [PennyLane](https://pennylane.ai/) – for hybrid (quantum-classical) ML modeling
-  Python (NumPy, matplotlib) – data handling, analysis, and graphing

---

## Goals & Future Work

This project aligns with my interest in **QML** and **mathematics**. Over the coming months, I will: 
- Build and simulate small QNN models
- Experiment with how entangled qubits influence model expresiveness
- Visualize training performance and quantum state evolution
- Aspire to develop this into a deeper research project

### After MathQuantum

After this program, I plan to pursue independent research and improve on this framework – documenting my progress in GitHub and collaborating with mentors or researchers where possible.

---

### Thank you!

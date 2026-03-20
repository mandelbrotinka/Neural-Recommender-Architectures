# Neural-Recommender-Architectures
Deep Learning implementation of Movie Recommendation System. Developed at University of Vienna.

# Project Overview
This project features a complete, from-scratch implementation of a Multi-Layer Perceptron (MLP) using only NumPy. The primary objective was to deconstruct the "black box" of Deep Learning by manually coding the mathematical foundations of neural networks, including forward propagation, backpropagation, and gradient-based optimization.

Developed as part of the Master’s in Data Science at the University of Vienna, this implementation emphasizes algorithmic transparency and numerical stability in neural network training.

# Key Technical Features
Full Backpropagation Logic: Implemented manual gradient computation using the chain rule to update weights across multiple hidden layers.

Modular Activation Functions: * ReLU (Rectified Linear Unit) for hidden layers to mitigate vanishing gradients.

Sigmoid and Tanh support for diverse architectural experiments.

Advanced Loss Functions: Manual implementation of Hinge Loss and Cross-Entropy, allowing for both margin-based and probabilistic classification.

Parameter Optimization: Integrated weight update rules to ensure convergence on complex non-linear datasets.

Zero-Library Dependency: Built using only NumPy for linear algebra, ensuring a deep understanding of matrix operations and gradient flow.

# Tech Stack
Language: Python 3.10+

Core Logic: NumPy (Linear Algebra)

Visualization: Matplotlib (for loss and accuracy trajectory analysis)

Data Format: H5PY (for handling large-scale structured datasets)

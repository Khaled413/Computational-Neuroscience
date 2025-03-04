![DALL·E 2025-03-04 03 05 11 - A detailed and realistic horizontal illustration of a neural network demonstrating backpropagation with clear steps  The diagram should include__- An ](https://github.com/user-attachments/assets/062147ac-586f-4179-b1b4-4fcac3b4f617)
# Backpropagation from Scratch

## Overview
This project implements the **Backpropagation Algorithm** from scratch using only core Python (without NumPy). The code demonstrates how weights are updated in a simple neural network with one hidden layer.

## Features
- Fully manual **forward pass** calculations.
- Explicit **backpropagation** with detailed gradient calculations.
- **Weight updates** using gradient descent.
- **Error tracking** before and after weight updates.

## Network Structure
- **Inputs:** Two input neurons (`i1`, `i2`).
- **Hidden Layer:** Two neurons (`h1`, `h2`) with a sigmoid activation function.
- **Output Layer:** Two neurons (`o1`, `o2`) with a sigmoid activation function.

## Mathematical Formulation
The calculations follow the step-by-step backpropagation process:
1. **Forward Pass**: Compute the weighted sum (`net`) and activation (`out`) for each neuron.
2. **Compute Error**: Calculate the total error using the squared error loss function.
3. **Backward Pass**: Derive gradients for weights using the chain rule.
4. **Update Weights**: Apply gradient descent to adjust weights.
5. **Recompute Forward Pass**: Check if the error has decreased.

## Expected Output
The program prints:
- The total error before weight updates.
- The total error after weight updates.
- The updated weight values.

If the total error decreases after updates, the backpropagation is working correctly.

## Author
Developed by **Khaled Ali** as part of a neural network backpropagation study.


# Perceptron Explanation and Decision Boundary

## Understanding the Perceptron
A perceptron is a fundamental unit of a neural network. It takes weighted inputs and applies an activation function to determine the output.

![Perceptron Diagram](images/perceptron.png)

---

## How the Decision Boundary is Calculated

The perceptron equation is:

\[
w_1 \cdot x_1 + w_2 \cdot x_2 + b = 0
\]

Solving for \( x_2 \):

\[
x_2 = -\frac{w_1}{w_2} x_1 - \frac{b}{w_2}
\]

Given:
- \( w_1 = 0.6447 \)
- \( w_2 = -0.69 \)
- \( b = -0.34 \)

Final equation:

\[
x_2 = 0.934 x_1 - 0.493
\]

This line represents the **decision boundary** learned by the perceptron.

---

## "How You Did This Math"
We isolated \( x_2 \) to express the perceptron's boundary as a line equation for plotting purposes.

# Newton-Raphson Optimization Algorithm

This repository contains MATLAB code that implements the Newton-Raphson optimization method to find the minimum point of a given multivariable function. The approach leverages second-order derivatives for precise and efficient convergence.

This code was developed as part of our Optimization course project at IASBS, in collaboration with my groupmate, [Erfan Faridi](https://github.com/erfanfaridii/).

---

## Features

- **Function Contour Plot**: Visualizes the optimization process on a contour plot of the function.  
- **Newton-Raphson Algorithm**: Utilizes the gradient and Hessian matrix to compute the optimal step direction.  
- **Dynamic Learning Rate**: Integrates methods like Backtracking (BT) to adjust the learning rate dynamically for convergence.  
- **Customizable Parameters**: Easily modify the starting point, function, and other parameters.  
- **Visualization of Progress**: Tracks the optimization path and overlays it on the contour plot.  

---

## Prerequisites

- **MATLAB**  
Ensure you have MATLAB installed on your system. The code uses built-in MATLAB functions such as `gradient`, `hessian`, and symbolic computations with `syms`.

---

## Usage

1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/NewtonRaphson_Optimization.git
   cd NewtonRaphson_Optimization
   ```

2. Open MATLAB and navigate to the folder.

3. Run the main script:
   ```matlab
   NewtonRaphsonOptimization.m
   ```

4. Modify parameters such as the initial point, the function definition, or the learning rate method as needed.

---

## Output

- **Optimization Path**: Displays the sequence of points leading to the minimum on the contour plot.  
- **Result Summary**: Prints the minimum point, the number of iterations, and the function value at the minimum in the MATLAB console.

---

## Example

For the provided function:
```matlab
f(x1, x2) = -cos(x1) * cos(x2) * exp(-(x1 - pi)^2 - (x2 - pi)^2);
```
The script identifies the minimum point, tracks its path, and displays the results.

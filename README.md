# Numerical Solution to the Optimal Portfolio Selection Problem for Power Utility Function

This repository contains the code and PDF reference for solving the optimal portfolio selection problem using a power utility function.

## Problem Overview
An investor aims to maximize her terminal wealth subject to utility constraints. The solution involves an algorithm that utilizes **[maximal central differencing](https://www.jstor.org/stable/40233269)**. The algorithm prefers central differencing as long as it satisfies the positive coefficient criteria. If this is not possible, it will select either forward or backward differencing based on which method meets the criteria.

## Methodology
The approach is based on maximizing central differencing within the constraints of the algorithm. For more details on the methodology, refer to the linked PDF below.

## Resources

- [Methodology PDF](https://github.com/kenrickraymond/Numerical-Solution-to-the-Optimal-Portfolio-Selection-Problem-for-Power-Utility-Function/blob/main/Numerical%20Solution%20to%20the%20Optimal%20Portfolio%20Selection%20Problem%20for%20Power%20Utility%20Function.pdf): A brief explanation of the methodology used in the algorithm.
  
- [Implementation Code](https://github.com/kenrickraymond/Numerical-Solution-to-the-Optimal-Portfolio-Selection-Problem-for-Power-Utility-Function/blob/main/Numerical%20Solution%20to%20the%20Optimal%20Portfolio%20Selection%20Problem%20for%20Power%20Utility%20Function.ipynb): The Python code used to implement the solution to the portfolio selection problem.

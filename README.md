## Introduction

Solidity is a high-level programming language for implementing smart contracts on blockchain platforms like Celo. A common problem in programming is dealing with arithmetic operations that may result in overflows or underflows. In this challenge, you'll be creating a Safe Math library in Solidity to handle these scenarios safely.

## Problem Statement

Design a Safe Math library that provides functions for addition, subtraction, multiplication, and division with the following requirements:

1. The library should prevent overflow in addition and multiplication operations.
2. It should prevent underflow in subtraction operations.
3. It should handle division by zero in division operations.
4. It should be capable of handling unsigned integers.

## Hints

- Use Solidity's `library` keyword to define your Safe Math library.
- The `require()` function can be used to enforce conditions and revert transactions.
- To prevent overflow, you can check if the result of an operation is greater than one of the operands (for addition and multiplication).
- To prevent underflow, you can check if the result of a subtraction is less than one of the operands.
- Ensure the denominator is greater than zero in division operations.

## Evaluation Criteria

- **Correctness**: The library should compile without errors and meet all the requirements.
- **Readability**: The library should be well-documented, with comments explaining each function.
- **Testability**: You should provide examples of how to test each function of the library.

Note that this challenge does not cover various other aspects such as gas efficiency or using other data types, which are crucial for real-world applications on Celo.

For a complete understanding of Celo smart contracts and Solidity, please refer to the Celo and Solidity tutorials.

## Submission

Please provide a link to your PR on GitHub, including your Safe Math library. Also include any notes, comments, or design choices you think are important for understanding your solution. Lastly, provide a brief explanation about how each function of the library should be tested.

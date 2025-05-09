# Introduction to Derivatives

Excellent work with limits! Now we'll use what you've learned to understand derivatives - the heart of differential calculus.

## What is a Derivative?

A derivative measures the rate of change of a function. It tells us how quickly a function's output is changing with respect to its input.

The derivative of a function f(x) is denoted as:

- f'(x) (read as "f prime of x")
- df/dx (read as "d f d x")

## The Formal Definition

The derivative is defined using limits:

f'(x) = lim(h→0) [f(x+h) - f(x)]/h

This formula finds the instantaneous rate of change by taking smaller and smaller intervals (h).

## Understanding Derivatives Visually

Geometrically, the derivative at a point represents the slope of the tangent line at that point.

For example:

- If f'(x) = 3, the function is increasing at a rate of 3 units per unit of x
- If f'(x) = 0, the function has a horizontal tangent line (not increasing or decreasing)
- If f'(x) = -2, the function is decreasing at a rate of 2 units per unit of x

## Example: Finding a Derivative Using the Definition

Let's find the derivative of f(x) = x² using the limit definition:

f'(x) = lim(h→0) [(x+h)² - x²]/h
     = lim(h→0) [x² + 2xh + h² - x²]/h
     = lim(h→0) [2xh + h²]/h
     = lim(h→0) [h(2x + h)]/h
     = lim(h→0) [2x + h]
     = 2x

So the derivative of x² is 2x!

## Exercise 3: Exploring Derivatives

1. Using the definition of the derivative as a limit, find the derivative of f(x) = 3x + 1.

2. For the function g(x) = x², calculate:
   a) g'(2)
   b) What does this value tell you about the function at x = 2?

3. The position of a moving object is given by s(t) = t² - 4t + 5, where t is time in seconds.
   a) Find the velocity function v(t)
   b) Find the velocity at t = 3
   c) Is the object moving forward or backward at t = 1?

4. For each of these cases, determine if the derivative would be positive, negative, or zero:
   a) A function at a point where it's increasing
   b) A function at its maximum value
   c) A function at a point where it's decreasing
   d) A linear function with negative slope

---

After completing these problems, we'll move on to derivative rules that will make calculations much easier!
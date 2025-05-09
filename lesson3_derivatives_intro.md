# Introduction to Derivatives: A Beginner's Guide

Excellent work with limits! Now we'll use what you've learned to understand derivatives - the heart of differential calculus.

## What is a Derivative? (In Simple Terms)

Think of a derivative as the "speedometer" of a function. Just like a car's speedometer tells you how fast you're going at each moment, a derivative tells you how quickly a function's values are changing at each point.

In everyday terms:

- If you're walking uphill, the steepness of the hill at each point is like the derivative
- If you're tracking temperature throughout the day, the rate at which it's warming or cooling at each moment is the derivative
- If you're watching a car move, its speed at each moment is the derivative of its position

## Real-World Meaning of Derivatives

The derivative measures:

- Rate of change
- Slope at a point
- How sensitive one value is to changes in another

## The Two Common Notations

The derivative of a function f(x) is written as:

- f'(x) (read as "f prime of x")
- df/dx (read as "d f d x")

Both mean the same thing: the rate at which f(x) changes as x changes.

## The Formal Definition Made Simpler

The formal definition uses limits:

f'(x) = lim(h→0) [f(x+h) - f(x)]/h

What this really means:

1. Take a point x on your function
2. Take another point a tiny step (h) away: (x+h)
3. Calculate the slope of the line between these points: [f(x+h) - f(x)]/h
4. Make h smaller and smaller, approaching zero
5. The slope approaches the exact slope at point x

## Visual Understanding with a Picture

Imagine you have a curved line (a function). If you zoom in closer and closer to a single point on that curve, eventually it starts to look like a straight line. The slope of that straight line is the derivative at that point.

![Derivative as tangent line](https://upload.wikimedia.org/wikipedia/commons/thumb/0/0f/Tangent_to_a_curve.svg/400px-Tangent_to_a_curve.svg.png)

## What Derivative Values Tell You

- **Positive derivative (f'(x) > 0)**: Function is increasing (going up)
- **Negative derivative (f'(x) < 0)**: Function is decreasing (going down)
- **Zero derivative (f'(x) = 0)**: Function is flat at that point (not increasing or decreasing)
- **Larger derivative value**: Function is changing more rapidly

## Step-by-Step Example: Finding a Derivative

Let's find the derivative of f(x) = x² using the definition:

1. Start with the definition:
   f'(x) = lim(h→0) [f(x+h) - f(x)]/h

2. Replace f(x) with x² and f(x+h) with (x+h)²:
   f'(x) = lim(h→0) [(x+h)² - x²]/h

3. Expand (x+h)²:
   f'(x) = lim(h→0) [x² + 2xh + h² - x²]/h

4. Cancel out x² terms:
   f'(x) = lim(h→0) [2xh + h²]/h

5. Factor out h:
   f'(x) = lim(h→0) [h(2x + h)]/h

6. Cancel h (note: we can do this because h≠0 before we take the limit):
   f'(x) = lim(h→0) [2x + h]

7. Apply the limit (as h approaches 0):
   f'(x) = 2x

So the derivative of x² is 2x!

## Another Simple Example

For f(x) = 3x, let's find f'(x):

1. Apply the definition:
   f'(x) = lim(h→0) [(3(x+h)) - 3x]/h

2. Simplify:
   f'(x) = lim(h→0) [3x + 3h - 3x]/h

3. Cancel terms:
   f'(x) = lim(h→0) [3h]/h

4. Simplify:
   f'(x) = lim(h→0) [3] = 3

So the derivative of 3x is just 3!

## Velocity: A Real-World Application

If s(t) represents an object's position at time t:

- s(t) is the position function
- s'(t) is the velocity function (the derivative of position)

For example, if a car's position is s(t) = t², then its velocity is s'(t) = 2t.

- At t=1 second, velocity = 2(1) = 2 meters/second
- At t=5 seconds, velocity = 2(5) = 10 meters/second

## Exercise 3: Exploring Derivatives

1. Using the definition of the derivative as a limit, find the derivative of f(x) = 3x + 1.
   (Hint: Follow the step-by-step approach we used above)

2. For the function g(x) = x², calculate:
   a) g'(2) (We already know g'(x) = 2x, so calculate the value when x=2)
   b) What does this value tell you about the function at x = 2?

3. The position of a moving object is given by s(t) = t² - 4t + 5, where t is time in seconds.
   a) Find the velocity function v(t) (remember, velocity is the derivative of position)
   b) Find the velocity at t = 3
   c) Is the object moving forward or backward at t = 1? (Hint: forward means positive velocity)

4. For each of these cases, determine if the derivative would be positive, negative, or zero:
   a) A function at a point where it's increasing
   b) A function at its maximum value
   c) A function at a point where it's decreasing
   d) A linear function with negative slope

---

After completing these problems, we'll move on to derivative rules that will make calculations much easier!
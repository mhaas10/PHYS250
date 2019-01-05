# PHYS250 assignment 4: Understanding and using Newton's Method and others for root finding

## Rootfinding

Rootfinding is the process of solving $F(x) = 0$ for $x$.  The standard assumption is that $F : R \to R$ is _continuous_.  We are interested in developing general-purpose algorithms---those that can use $F(x)$ without needing to know many details about the function itself except that it satisfies basic generic properites of "well-behaved" functions.  When we implement our rootfinding algorithm in software, the user will pass a function or program to compute $F(x)$.  Rootfinding methods for differentiable functions may also use the derivative $F'(x)$.

Some questions immediately arise:
* **Existence.** When does this equation have at least one solution?
* **Uniqueness.** When is the solution unique?

In this homework, you will consider aspects of the numerical methods that we've discussed and apply slight variations and improvements on those as you work through the details of the exercises and learn the limitations that the methods have.


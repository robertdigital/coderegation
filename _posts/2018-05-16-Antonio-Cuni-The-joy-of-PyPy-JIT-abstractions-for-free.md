---
speaker: Antonio Cuni
topic: The joy of PyPy JIT - abstractions for free
video: https://www.youtube.com/watch?v=NQfpHQII2cU
issue: 153
---

The PyPy JIT is a powerful piece of technology which makes Python program running faster: in this talk, we will see how it helps us to write our programs better without sacrificing performance. One of the key to write complex software systems of good quality is to make a good usage of abstractions, to clearly separate the various layers and components. However, often each layer of abstraction adds some cost in terms of runtime performance, so we need to struggle finding the best trade-off between maintainability and speed. Because of the way it works, the PyPy JIT naturally removes the cost of most abstractions: we will look at real-life examples of how this is possible, showing what the JIT can and can't do. We will also show how this compares to other popular systems of optimizing Python code, such as Cython.


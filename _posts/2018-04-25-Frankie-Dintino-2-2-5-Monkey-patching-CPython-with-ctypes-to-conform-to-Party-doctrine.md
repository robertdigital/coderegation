---
speaker: Frankie Dintino
topic: 2 + 2 = 5 - Monkey-patching CPython with ctypes to conform to Party doctrine
video: https://www.youtube.com/watch?v=tZ3ZfBX61eE
issue: 150
---

A few weeks into your tenure as a software engineer at the Ministry of Truth you are assigned your first real feature request: write a context manager that can make “2 + 2” equal 5 at runtime. Your solution should be written only in Python (for maximum portability). Absurd? Perhaps, but you know better than to ask questions. You are no thought-criminal.

In this talk I walk through the steps I took to modify the value of two plus two in CPython at runtime—using only Python and the ctypes module. What began for me as a silly and frivolous side project became an education in how the python data model works behind the scenes and how CPython compiles, optimizes, and executes python code.

The goal of this talk is to provide an introduction to CPython internals while walking through the steps needed to monkeypatch integer addition to make “2 + 2” equal 5. The audience should come away with a better understanding of how python objects and types are represented in memory, how references are counted, and how python scripts are transformed into abstract syntax trees, compiled into code objects, and then executed by the CPython virtual stack machine. And because I’ve limited myself to using ctypes, these topics can be explored without familiarity with C as a prerequisite.


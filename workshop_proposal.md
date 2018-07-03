# Symbolic Computation with Python using SymPy

In this tutorial, we will introduce attendees to SymPy, a computer algebra system (CAS) written in Python. We will show basics of constructing and manipulating mathematical expressions in SymPy, the most common issues and differences from other computer algebra systems, and how to deal with them. In the last part of this tutorial, we will show how to solve practical problems with SymPy. This will include showing how to interface SymPy with popular numeric libraries like NumPy.

Attendees will take home an introductory level understanding of SymPy. This knowledge should be enough for attendees to start using SymPy for solving mathematical problems and hacking SymPy's internals (though hacking core modules may require additional expertise).

SymPy is a pure Python library for symbolic mathematics. It aims to become a full-featured computer algebra system (CAS) while keeping the code as simple as possible in order to be comprehensible and easily extensible. The tutorial will cover the following topics and more.

```
Introduction
    What is Symbolic Computation?
    A More Interesting Example
    The Power of Symbolic Computation
    Why SymPy?
Gotchas
    Symbols
    Equals signs
    Two Final Notes: ^ and /
Basic Operations
    Substitution
    Converting Strings to SymPy Expressions
    evalf
    lambdify
    Printing
    Printers
    Setting up Pretty Printing
    Printing Functions
    Simplification
    simplify
    Polynomial/Rational Function Simplification
    Trigonometric Simplification
    Powers
    Exponentials and logarithms
    Special Functions
Calculus
    Derivatives
    Integrals
    Limits
    Series Expansion
    Finite differences
    Solvers
    A Note about Equations
    Solving Equations Algebraically
    Solving Differential Equations
Matrices
    Basic Operations
    Basic Methods
    Matrix Constructors
    Advanced Methods
Advanced Expression Manipulation
    Understanding Expression Trees
    Recursing through an Expression Tree
```

# Prerequisites:

The tutorial will only assume a basic knowledge of Python. No prior knowledge of SymPy or other Python libraries is required, although it is suggested that attendees be familiar with the IPython notebook. A mathematical knowledge of calculus is recommended.

We recommend that the attendees install the Anaconda Python distribution which includes SymPy, NumPy, and IPython. Once Anaconda is installed simply type the following in a terminal to install the necessary packages:
```
$ conda install numpy ipython-notebook sympy
```
Other alternative installation instructions can be found here: http://docs.sympy.org/dev/install.html

# Content URLs:

SymPy team has developed and delivered many talks and tutorials at SciPy and other conferences. 
We are constantly building on new content and improving the present at the same time. 
The website for the workshop at PyCon India 2015 is [here](http://iamit.in/sympy-tutorial/html/). 
You can find the introduction slides [here](http://iamit.in/sympy-tutorial/pycon2015.pdf), the sphinx tutorial [here](http://iamit.in/sympy-tutorial/html/) and the exercises in form of IPython notebooks.

Note: the notebooks are hosted statically, you can download from [here](http://iamit.in/sympy-tutorial/tutorial_exercises.zip) and run locally to have an interactive session.

# Speaker Info:

SymPy India developers will be conducting the workshop: 

* [Sidhant Nagpal](https://github.com/sidhantnagpal): NSIT Delhi | Core Developer at SymPy, GSoC 2018 | Discrete module
* [Yathartha Joshi](https://github.com/Yathartha22): BTKIT Dwarahat | Core Developer at SymPy, GSoC 2018 | Solvers module
* [Ravicharan](https://github.com/RavicharanN): IIIT Allahabad | Core Developer at SymPy, GSoC 2018 | Combinatorics module
* [Shekhar Prasad Rajak](https://github.com/Shekharrajak): GSoC 2016 | Solvers
* [Jashanpreet Singh](https://github.com/jashan498): TIET Patiala | Core Developer at SymPy, GSoC 2018 | Beam Bending module

# Speaker Links:

* Resource repository: https://github.com/sidhantnagpal/sympy-tutorial/tree/PyConIndia18
* SymPy website: http://www.sympy.org/en/index.html 
* SymPy live: http://live.sympy.org/ 
* GitHub repository: https://github.com/sympy/sympy

**Link to previous SymPy Tutorials/Talks**

* Automatic Code Generation with SymPy, SciPy 2017: [https://www.youtube.com/watch?v=5jzIVp6bTy0](https://www.youtube.com/watch?v=5jzIVp6bTy0)
* SymPy, EuroSciPy 2017: [https://www.youtube.com/watch?v=nfRyux3wEhw](https://www.youtube.com/watch?v=nfRyux3wEhw)
* Symbolic Compution with Python using SymPy Beginner, SciPy 2016: [https://www.youtube.com/watch?v=AqnpuGbM6-Q](https://www.youtube.com/watch?v=AqnpuGbM6-Q)
* SymPy Tutorial, SciPy 2014: [https://www.youtube.com/watch?v=Lgp442bibDM](https://www.youtube.com/watch?v=Lgp442bibDM)
* SymPy Tutorial, SciPy 2013: [https://www.youtube.com/watch?v=dAgShwIx72c](https://www.youtube.com/watch?v=dAgShwIx72c)
* PyCon India - 2017 : [Computer aided algebra system (CAS) for different programming languages using SymEngine and SymPy](https://in.pycon.org/cfp/2017/proposals/computer-aided-algebra-system-cas-for-different-programming-languages-using-symengine-and-sympy~eXnob/)

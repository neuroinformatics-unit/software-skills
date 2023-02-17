# Type annotation in Python

### Overview
The Python programming language has become the de facto standard for writing a vast majority of scientific code. While being highly general-purpose (unlike alternatives like matlab or R), Python is interpreted and dynamically-typed. On the one hand, these properties have spurred the emergence of interactive Python-powered development toolkits such as IPython or Jupyter, making it easy for scientists and software engineers to explore data and write Python code in an iterative manner. On the other hand, these properties imply that the type safety of a program is not checked by a compiler, but by the programmer, the remaining uncaught type errors being raised at runtime. Detrimental consequences follow: the mental charge of writing code increases, refactoring becomes daunting, interactive development loses in fluidity.

Type Hints, introduced in Python by PEP 484, seek to reintroduce type safety to Python programs, through the concept of “type annotations”. Type annotations are used in Python programs to declare the expected type of variables. These annotations do not affect runtime, but can be leveraged by static Python type checkers such as mypy or pyright to produce ahead-of-time warning messages describing the mismatch between a variable’s type annotation and its runtime type as predicted by the checker.

On the one hand, type annotations can be adopted gradually, inducing a low barrier to entry. On the other hand, a holistic usage of type hints requires some foundational knowledge of type theory, a subfield of theoretical computer science which is not frequently mastered by domain scientists.

In this tutorial, we will learn how to use Python type annotations: we will go through the basic type-theory prerequisites that are necessary for an informed usage of such annotations. We will make a panorama of the current available type-related features in Python, through a series of basic illustrative examples. Finally, we will discuss the additional features stemming from the integration of type annotations with popular code development toolchains (in particular Language Servers), leading to more informative completion and error checking.

Delivered by [Pierre Glaser](https://github.com/pierreglaser).

### Links
* [Slides](https://adamltyson.com/pyclub-typing/)

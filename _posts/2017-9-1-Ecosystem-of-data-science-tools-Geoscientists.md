---
layout: post
title: Ecosystem of data science tools for geologists
---
#### Free and open-source softwares (FOSS) for data science

![Ecosystem of tools](https://raw.githubusercontent.com/gcmatos/gcmatos.github.io/master/images/foss.png)

### Introduction

Geologists deal with data provided from Earth through measuring devices (e.g. compass, GPS, cameras, etc.) and we are constantly facing highly complex physical features and sparse datasets that can make us feel stuck and hopeless. Commercial softwares also don't provide all the resources needed for problem solving. We have to process a broad range of types and sizes of structured and unstructured raw data.

In this article I will give a glimpse on some of the main tools that I find useful in my daily activities as a geologist and data scientist. On each one of the following items you will find a brief description and key links for you to go further into your topics of interest. It isn't suppose to be a tutorial, I just pretend to give the reader some orientations in the data science world, based on my self-learning experience.

### Python ecosystem

**Python** is the first tool that I am going to explain. It is a multi-proposal interpreted programming language created by [Guido van Rossum](https://gvanrossum.github.io//) (first released in 1991) that is extensively used by scientists, developers, software engineers and hackers.
  Useful links:
- [python.org](https://www.python.org/) the official web-site of the Python Software Foundation
- [anaconda.com](https://www.anaconda.com/) which is a open-source platform for data science

In Python you can type in a command line and hit return key without the need of compile the code to see the results as:

```python
>>> # Python 3: Simple output example from python.org
... print("Hello, I'm Python!")
Hello, I'm Python!
```
> In this code snippet above, the `>>>` is the first line of the interpreter prompt, `#` means it is a comment line, `...` means the prompt continues on the second line with the function `print()`, and the last line is the output from the interpreter. It is very simple and straight forward.

You can find a diverse and extensive range of packages for Python at [PyPi](), each one designed for scientific and development tasks. There's a list below with the most popular Python packages for scientific computing, data exploration and machine learning:
- [Numpy]() / [Scipy]()
- [Pandas]()
- [Matplotlib]()
- [Scikit-learn]()

Recommended syntax for importing those packages:
```python
import numpy as np
import scipy as sp
import pandas as pd
import matplotlib as mpl
import scikit-learn as sklearn
```
### Jupyter notebooks
This is definitely the most popular tool for data exploration and modeling. Jupyter notebooks allow us to write code and well formatted comments, provide us with a dynamic way of collaborating and sharing knowledge among the the community of scientists and software developers.

Jupyter notebooks are built on iPython framework that flexible and can run different programming languages such as Python, R, Julia, C, Matlab, and many others. Each language is loaded as a kernel in the notebook. 

### R programming language
R is a programming language designed for statistics and scientific computing. You will find an extensive list of libraries that allow us to have access useful datasets and functions for data analysis in their repository [CRAN](https://cran.r-project.org/). R community also provide us with high level books, articles and tutorials.
  Useful links:
  - [R Tutorial](https://www.statmethods.net/r-tutorial/index.html)
  - [R for Data Science](http://r4ds.had.co.nz/) Amazing book written by Garrett Grolemund and Hadley Wickham.

...

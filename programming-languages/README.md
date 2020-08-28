# Programming Languages

## C++

### Tutorials

* [C++ Tutorials - Tutorialspoint ](https://www.tutorialspoint.com/cplusplus/index.htm)**_Why this Tutorial?:_** Live Online Coding !!!
**_What to keep in mind?:_** This tutorial only helps you understand the syntax of C++. To effective, one must follow this tutorial up with sources. 

### Books and Reference Material

* [Effective Modern C++](https://www.oreilly.com/library/view/effective-modern-c/9781491908419/)
**_Why this book?:_** The effective C++ series of books have been hailed as one of the best references for good C++ coding practices. It also provides a good introduction to several new language features. 

* [Tour of C++ Bjarne Stroustrup](https://isocpp.org/tour)
**_Why this book?:_** This provides the user with a general overview of C++. It talks about the different features about the language and how they can be used to support different programming paradigms.
**_What to keep in mind?:_** This book is not meant for beginners of C++. It is also not a complete reference for the language.

### Channels

* [CppCon Talks](https://www.youtube.com/user/CppCon)
* [C++ Weekly by Jason Turner](https://www.youtube.com/user/lefticus1)

### Tools

* [Compiler Explorer](https://godbolt.org/): Online C++ compiler. It lets you compile small code snippets and look at the generated assembly code. It supports different compilers across various architectures ranging from x86 to Arduinos.
* [JetBrains CLion](https://www.jetbrains.com/clion/): One of the best C++ IDEs. CLion works on CMake making it easy to use with roscpp. 


## Python
A high level, interpreted, dead-simple, reads-like-english programming language used for a multitude of tasks, from Machine Learning/Data Analysis to deploying Full-Stack Websites.

The [official website](https://www.python.org/) offers further resources, including talks, podcasts, conferences and the like.

### Tutorials

* [Sentdex Python Tutorial Series](https://www.youtube.com/playlist?list=PLQVvvaa0QuDe8XSftW-RAxdo6OmaeL85M): A collection of short videos that deal with everything from installing python, through loops, control flow, functions, upto usage of the package manager pip. Beyond this, the tutorial deals with specific use cases which may be skipped. It is highly recommended that you code along with the videos.

* [Python for everybody series on Coursera or py4e.com](https://py4e.com): This Specialization builds on the success of the Python for Everybody course and will introduce fundamental programming concepts including data structures, networked application program interfaces, and databases, using the Python programming language. In the Capstone Project, you’ll use the technologies learned throughout the Specialization to design and create your own applications for data retrieval, processing, and visualization.

* [Corey Schafer Python Series](https://youtu.be/YYXdXT2l-Gg): One of the most elegant courses on python. Covers python from basic to intermediate.  Covers topics like generators, threading on top of all the basic concepts. It is highly recommended that you code along with the videos. 

### IDEs

* [JetBrains' PyCharm](https://www.jetbrains.com/pycharm/): Fully featured Python IDE, offering powerful autocomplete, virtual environment support, comprehensive debugging, and notebook support. Users of other JetBrains IDEs will feel right at home. A student email-id will give you free access to the Professional Version that includes a specific mode for data science.
* [Jupyter Notebooks/ JupyterLab](https://jupyter.org/): Code in true interactive fashion, as you execute blocks and see outputs of unfinished code, which will help you code further. Runs in a browser, and a pip install is all that is required to get it.
* [vscode](https://code.visualstudio.com/): A lightweight, extensible IDE with support for autocomplete, error-checking,git, ssh support and ipynb notebooks. It has a very powerful debugger and a long list of useful extensions/plugins. This is the favourite IDE of most of the developers and data scientists. 

### Tools

* **Environment/Dependency management**: [Conda](https://docs.conda.io/) or [venv](https://docs.python.org/3/library/venv.html) are typically used to isolate multiple python environments, so you don't end up with conflicting dependencies for different projects. This is highly recommended. It may seem like an inconvenience at first, but will save you a lot of time later on. Conda is recommended for ML/DL related work, because this can handle CUDA and CUDNN within the Virtual Environment, and a system-wide install is not required. Conda environments take up much more space than their venv counterparts.

### Notable Libraries:
* [NumPy](https://numpy.org/): Handles all sorts of Linear Algebra, and it's data-types are used in most other mathematical libraries.
* [Matplotlib](https://matplotlib.org/): Plots and Visualizes all of your data.
* [Pandas](https://pandas.pydata.org/): Can be used for handling data files such as .csv, .xlsx. Has deep integration with NumPy and Matplotlib.
### Inbuilt Libraries
It is highly recommended to take the time and get familiar with the standard library (of sorts) of Python. The included tools like itertools, collections, and others. They provide implementations of all sorts of cumbersome things, like sorting, min/max, list comprehension and others, as functions. These will help you write code in true Python fashion, abstracting out everything but your main business logic. 
**Before writing cumbersome/boilerplate code, Google.**

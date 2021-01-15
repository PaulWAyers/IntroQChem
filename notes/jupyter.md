# Jupyter and Computer Programming

Throughout this course, we will use *Jupyter* notebooks to explore the material. Your first assignments will provide you with some basic background in *Jupyter*, *Python*, and *Numpy*. (I had been hoping to use *Julia*, which is arguably easier, but the online tools available at McMaster seem not to support *Julia*.)

## Overview of Programming 
In this course, we will primarily use the [Python](https://www.python.org/) programming language. The best way to learn a programming language is to practice it on your own and learn through trial and error. Making mistakes helps you improve, so if at any point you get stuck, don’t get discouraged, seek help, and keep coding! There are many great resources online for learning about programming, so the course content for this topic is mostly based on external sources, especially [LinkedIn Learning](https://lnkd.in/gj-9Xgg). 

## What is Programming?
Programming is the process of writing a set of instructions (like a step-by-step recipe) that tells a computer how to perform a certain task. This recipe is written in a code called programming language. Similar to human languages, programming languages have syntax (the rule for writing instructions) and semantics (the meaning of the instructions). Also like human languages, there are lots of programming languages to choose from, each of these languages has its own history, features, and applications, but they all share the same fundamental ideas. You will learn more about programming languages by watching this 3-minute YouTube video [here](https://www.youtube.com/watch?v=EGQh5SZctaE).

The most popular programming languages are either interpreted or compiled. For example, Python is an interpreted language. The Python interpreter reads a set of code instructions written in Python and translates it into a set of instructions for the computer to follow, and these instructions are then executed. This is analogous to the way a human language interpreter translates the spoken word from one language to another, on the fly. Compiled languages in compiled languages like C++ or Fortran, an entire computer program (or a large section thereof) is translated into instructions for the computer to follow, which is subsequently executed. This is analogous to the way a human translator might translate a book: the book is translated one chapter at a time, and perhaps content is rearranged to make it more idiomatic for the new language; then the book is read. Some other languages (e.g., Julia) are just-in-time translated, which is like translating a book chapter only after you are sure someone will read it, and potentially catering your translation to the particular person reading the book. Obviously compiled languages can be more efficient computationally, but they are also more complicated to use because the modules of the computer program must be translated from the human-readable computer language to machine-readable instructions("compiled"), then combined together ("linked"), before they are finally executed. In this course we will use mainly Python, which is an interpreted language.

Computers always do *exactly* what they are told to do, so when you write a program, it is important to be clear, precise, and explicit about what you want the computer to do.  So it is very important to learn the syntax and semantics of the language you use. 

## Why Learn to Program?
While computers always do *exactly* what you tell them to do, so in some sense they cannot do anything you could not do yourself. However, they allow you to perform those actions more efficiently. As Steve Jobs says, [a computer is a bicycle for the mind](https://www.youtube.com/watch?v=ob_GX50Za6c). And thus learning to program a computer is like learning to ride a bicycle. 
## Why Learn [Python](https://docs.python.org/3/)?
There are many programming languages out there, and each language has its unique advantages and disadvantages. Once you learn the basics of programming in one language, you can generally apply the same concepts to other languages. Python is one of the fastest-growing programming languages (Dropbox, Instagram, Netflix, and Google use Python extensively) and it is increasing popular in chemistry too. For more about the advantages of Python, watch the [video segment](https://www.linkedin.com/learning/programming-foundations-fundamentals-3/why-python?u=56982905)

Compared to most other languages, Python is easier to read and write. It's syntax is relatively simple, yet it's flexibility -- it's ability to perform tasks from web development to scientific computing -- is nearly unsurpassed. Importantly, there are a large number of plug-and-play Python libraries, which allow one to extend the basic features of the Python language with additional features. We will, for example, find the Numpy and Scipy libraries especially helpful.
## What is [Jupyter](https://jupyter-notebook.readthedocs.io/en/stable/index.html)?
To write and execute your code, you need to have access to the appropriate intepreters/compilers either through a web brower or locally on your computer. In this course, we will be using online Jupyter notebooks. Jupyter notebooks provides an interactive computing environment, originally focussed on [**Ju**lia](), [**Py**thon](), and [**R**](https://jupyter.org/), though other languages are supported now.

## What is Numpy?

## Getting Started

### Log into Syzygy
In this course, we will use a *JupyterHub* that is provided free to most Canadian university students called [syzygy.ca](https://mcmaster.syzygy.ca/). Please
1. Log into [syzygy.ca](https://mcmaster.syzygy.ca/). This is a *JupyterHub*.
2. Read the [tutorial](https://intro.syzygy.ca/), especially the documentation on [opening](https://intro.syzygy.ca/the-basic-elements/) and [using](https://intro.syzygy.ca/python-for-computing/) a Python 3 notebook. Opening a new empty notebook is as simple as clicking "New -- Notebook -- Python 3". 

### LinkedIn Learning Courses
To learn more about Jupyter, programming concepts, Python programming, and Numpy, your first assignments are LinkedIn Learning courses. Before you get started, it's helpful to log into LinkedIn Learning. (However, the links provided should automatically prompt you to log in if you are not already.) If you already have a LinkedIn account associated with a different e-mail, you can link your accounts. Upon completing each course, download your certificate of completion and upload it as your assignment. You can also add the certificate to your LinkedIn profile.
https://www.linkedin.com/learning-login/?account=2204553&authUUID=11Laiy7iSTyAdZ9%2BMwYn%2FA%3D%3D&redirect=https%3A%2F%2Fwww.linkedin.com%2Flearning%2Fme%3Fu%3D2204553

### Local Installation of Jupyter (optional)
If you would like to use Python and Jupyter locally, the easiest way to do this is probably by using the Anaconda distribution of Python, which simplifies many of the challenges a new programmer will encounter. For example,  Anaconda’s package manager allows you to easily install different versions of Python and third-party Python packages for various operating systems, including:
- [Mac OS X](https://docs.anaconda.com/anaconda/install/mac-os/)
- [Windows](https://docs.anaconda.com/anaconda/install/windows/)
- [Linux](https://docs.anaconda.com/anaconda/install/linux/)

You can then open the Anaconda Navigator and launch a Jupyter Notebook.


Please go through the content of the Introducing Jupyter course step-by-step and take the time to practice the material covered in your Jupyter notebook. Upon completing this course, you can upload your certificate of completion as Assignment 2.
https://www.linkedin.com/learning/introducing-jupyter/

Assignment: Please complete the LinkedIn Learning "Introducing Jupyter" course from Week 2 (see "Jupyter Notebook" section) and submit your certificate.
 

Python Programming
For instructions on how to get access to the LinkedIn Learning courses using your Queen’s email, see the “How to Get Started?” section.

Please go through the content of the Python Quick Start course step-by-step and take the time to practice the material covered in your Jupyter notebook. Upon completing this course, you can upload your certificate of completion as Assignment 3. 
https://www.linkedin.com/learning/python-quick-start/

Assignment: Please complete the LinkedIn Learning "Python Quick Start" course from Week 2 (see "Python Programming" section) and submit your certificate.
 
Numpy Library
Numpy is one of the most commonly used Python libraries for mathematical operations on vectors and matrices (aka linear algebra). It will not only used in our hands-on exercises, tutorials, and assignments in this course (as presented in Week 3 Hands-on Exercises) but also it is used by many computational chemistry Python packages that we are or will be using in this course.

As a result, it is important to take some time and familiarize yourself with Numpy. Please go through:
-	Numpy Introduction from W3Schools: 
https://www.w3schools.com/python/numpy_intro.asp
This interactive tutorial introduces you to the Numpy library and allows you to run the examples in the browser.
-	These 4 short videos are cherry-picked from LinkedIn Learning to give you an overview of Numpy and teach you how to create, index, and slice arrays and do math with them. The three Jupyter notebooks used are XXX, XXX, and XXX.
o	https://www.linkedin.com/learning/python-data-analysis-2015/numpy-overview?u=2204553
o	https://www.linkedin.com/learning/python-data-analysis-2015/creating-numpy-arrays?u=2204553
o	https://www.linkedin.com/learning/python-data-analysis-2015/doing-math-with-arrays?u=2204553
o	https://www.linkedin.com/learning/python-data-analysis-2015/indexing-and-slicing?u=2204553
-	(Additional resource) “Numpy: The absolute basics for beginners” provided by Numpy’s official website. (link: https://numpy.org/doc/stable/)

Assignment: Numpy is one of the most commonly used Python libraries for mathematical operations on vectors and matrices (aka linear algebra). It will not only used in our hands-on exercises, tutorials, and assignments in this course (as presented in Week 3 Hands-on Exercises) but also it is used by many computational chemistry Python packages that we are or will be using in this course.

As a result, it is important to take some time and familiarize yourself with Numpy. Please complete the LinkedIn Learning "Numpy Data Science Essential Training" course and submit your certificate. This course also teaches you about [Matplotlib](https://matplotlib.org/), the library we use for visualization.
https://www.linkedin.com/learning/numpy-data-science-essential-training/
Please Note:
1.	This course would be the most useful if you have a Jupyter notebook open and try the presented code snippets yourself.
2.	Feel free to skip "Numpy, data science, IMQAV" under the "Introduction" section, because it is not relevant to our course.
3.	Feel free to skip "Install Software" under the "Introduction" section, because you have already installed Anaconda.
4.	Feel free to skip "7. Extended Examples" section, because the examples given are not directly useful for our course, even though they are good Numpy practice cases.

 


## Learning Objectives
- Fundamental programming concepts
- Computer programming technical jargon (interpreter, syntax, semantics, execution, etc.)
- Basics of Python programming language and its benefits
- How to use Jupyter
- How to use Numpy

## Additional Learning Resources
There are *many* free and paid resources available for deepening your knowledge of Python including videos, tutorials, courses, and books. The following are recommended. For tutorial-based courses, if you can somehow document your completion of the tutorial, then you can submit the proof of your completion for extra credit.
1. Learn Python – Full Course for Beginners. This is indexed so you can skip to the topic you would like to learn about. [video](https://www.youtube.com/watch?time_continue=41&v=rfscVS0vtbw&feature=emb_logo)
1. Python Tutorial - Python for Beginners [video](https://www.youtube.com/watch?v=_uQrJ0TkZlc)
1. Learn Python [interactive tutorials](https://www.learnpython.org/)
1. The Python Tutorial [tutorial](https://docs.python.org/3/tutorial/)
1. Python Tutorial from W3School [tutorial](https://www.w3schools.com/python/default.asp)
1. The Incredible Growth of Python: [web site](https://stackoverflow.blog/2017/09/06/incredible-growth-python/)
1. Introducing Python to Chemistry Students: [web site](https://pythoninchemistry.org/)
1. Introduction to Julia (assumes prior programming knowledge). [interactive video tutorials](https://juliaacademy.com/p/intro-to-julia).
1. List of Julia tutorials [web based](https://julialang.org/learning/tutorials/)
1. Think Julia [free online book](https://benlauwens.github.io/ThinkJulia.jl/latest/book.html)
1. Intro to Julia [video](https://www.youtube.com/watch?v=8h8rQyEpiZA&t)
1. Numpy tutorial [web site](https://numpy.org/doc/stable/user/quickstart.html)

<br/><br/>

>> Hat-tip: Farnaz Heidar-Zadeh at Queens University, who curated much of this material.




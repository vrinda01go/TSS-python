# TSS-python
# **Welcome to Week 1 of Learner Space's Python!**

For the first week we will be covering some basic topics:

* Installation and Setup
* Introduction to Jupyter Notebooks
* Google Colab
* Introduction to Data Types and Data Structures in Python
* Operators in Python
* Conditions and Loops
* Iterators
* Python Functions
* Scope of Variables
* Recursion
* Python Modules and Packages
* Classes and Objects
* Constructors and Destructors in Python
* File Handling


We will be taking a very elementary approach for this course so that even a complete beginner can learn to code in Python. Python is the most diverse language with very varied applications in different fields such as Research, Machine Learning, Backend Web Development, Data Visualisation, Web Scraping and much more, and this is possible only because of the different libraries and frameworks available for Python. We will be covering various interesting applications of python in later part of the course, so Stay Tuned!
Let's get started!

## **Installation and Setup**

Visit this link for a detailed guide on installing and setting up Python - [Python Installation and Setup](https://wiki.python.org/moin/BeginnersGuide/Download)

## **Introduction to Jupyter Notebooks**

Jupyter notebook is a web based notebook environment which is widely used for interactive programming, that is, code execution combined with rich markdown text and much more. The Jupyter notebook runs a local Ipython kernel on your machine and launches in your web browser. These notebooks are also called as Ipython notebooks, and have a '.ipynb' extension instead of traditional '.py' extension for Python files. All the assignments for this course are made in Jupyter notebooks and you are expected to complete them in the notebook itself. Hence, it is important for you to get aquainted with Jupyter notebooks.

Visit this link for installing and setting up a basic notebook - [Setting up Jupyter Notebook](https://realpython.com/jupyter-notebook-introduction/). The link also teaches you to write and execute a basic Python code in a Notebook cell.

## **Google Colab**
Google Colab is a platform provided by Google, which runs a Jupyter notebook in the cloud. While it is a convenient way to get set up, there are some caveats you would like to know before it.
The setup is platform agnostic i.e. all you need is a browser. The recommended way to get started is first logging in to Google. Sign in > Head to the home page for Google Colab [here](https://colab.research.google.com/notebooks/intro.ipynb#recent=true) > click on New Notebook.
From this point, everything is basically the same as a Jupyter notebook.

## **Introduction to Data Types and Data Structures in Python**
Once you have set up the environment for writing your code, we now begin with coding in Python. Let's get started.

Head over to this link - [Introduction to Python Data Types](https://www.learnpython.org/en/Welcome) and start with the topics in the 'Learn the Basics' sections one by one (till 'Basic String Operations'). These are official tutorials from the Python organisation which are well curated for beginners and contain an inbuilt Ipython shell for writing and executing your code there itself.

If you are not of the reading kind, checkout this [Youtube playlist](https://www.youtube.com/playlist?list=PLzMcBGfZo4-mFu00qxl0a67RhjjZj3jXm) for step-by-step tutorials on Python basics (Tutorials #1 - #11 except #6, #7, #9). But make sure that you are following alongside with the video, otherwise things won't make sense later in the course.

You can also read these concepts from GeeksForGeeks. They explain each concept in good detail along with examples.

Irrespective of where you choose to read/watch from, you should be familiar with the following topics:
* [Strings](https://www.geeksforgeeks.org/python-strings/?ref=lbp)
* [Lists](https://www.geeksforgeeks.org/python-list/?ref=lbp)
* [Tuples](https://www.geeksforgeeks.org/python-tuples/?ref=lbp)
* [Sets](https://www.geeksforgeeks.org/python-sets/?ref=lbp)
* [Dictionary](https://www.geeksforgeeks.org/python-dictionary/?ref=lbp)
* [Arrays](https://www.geeksforgeeks.org/python-arrays/?ref=lbp)

## **Operators in Python**
Now that you have a basic idea about different variable data types and data structures, let us now explore how you can work with multiple variables at once in order to get your desired output. This is done using Operators.

Operators in a programming language mean the same thing as operators in maths (almost), so the only thing you need to be concerned about is the syntax of working with operators.

Head over to this link - [Python Operators](https://www.geeksforgeeks.org/python-operators/?ref=lbp) for a detailed description of different operators in Python. Then check out the tabs in the navigation bar on the left and read about all the operators one by one.
These are extremely important as some of the concepts explained here will be used to define other concepts later on, and to understand any piece of code analytically, you should know what each line of code is doing.
You should be familiar with the following Python operators:

* Arithmetic Operators
* Relational Operators
* Logical Operators
* Bitwise Operators
* Assignment Operators
* Identity Operators
* Membership Operators

## **Conditions And Loops**
Conditions and Loops are a core part of any program written in any programming language. You use loops whenever you want to perform a particular task repeatedly over many iterations, given a condition is satisfied. Conditions are also used without loops, as if-else conditions.

Checkout this link for a detailed article on Conditions and Loops - [Conditions](https://www.learnpython.org/en/Conditions) and [Loops](https://www.learnpython.org/en/Loops)
You can also refer to this link from GeeksForGeeks - [Conditions and Loops](https://www.geeksforgeeks.org/python-if-else/?ref=lbp) (Checkout all the tabs in the navigation bar on the left)
Again, if you prefer videos instead, refer to this [Youtube Playlist's Tutorial](https://www.youtube.com/playlist?list=PLzMcBGfZo4-mFu00qxl0a67RhjjZj3jXm) #6, #7 and #9.

Make sure you have covered the following topics -

* For loop
* while loop
* break statement
* continue statement
* If-else condition ( normal, nested, if-elif)

## **Iterators**
Iterator in python is any python type that can be used with a ‘for in loop’. Python lists, tuples, dicts and sets are all examples of inbuilt iterators. These types are iterators because they implement following methods.In fact, any object that wants to be an iterator must implement following methods.

__ iter__ method that is called on initialization of an iterator. This should return an object that has a next or __ next__ (in Python 3) method.

next ( __ next__ in Python 3) The iterator next method should return the next value for the iterable. When an iterator is used with a ‘for in’ loop, the for loop implicitly calls next() on the iterator object. This method should raise a StopIteration to signal the end of the iteration.

Check out this [Notebook](https://github.com/abhipaiangle/learners-space/blob/master/Python/Week%204/Notebook2.ipynb) to learn about Python Iterators.

To read more about Iterators refer [this](https://www.geeksforgeeks.org/iterators-in-python/)

## **Classes and Objects** 
A class is a user defined blueprint or prototype from which objects are created. It represents the set of properties or methods that are common to all objects of one type. You can think of a class as a collection of many different functions and attributes (variables) that can be accessed by an object of that class. These methods inside a class are defined almost in the same way normal Python functions are defined, with a major difference being the 'self' argument and some special methods only found in a class body, for example:- the '_init_' method, '_add_' method, etc.

An Object is a basic unit of Object Oriented Programming and a way to represent the classes you have declared in your program. And thus an object can also be sometimes called an instance of a class. Whenever you create an object of a class, you can access all the methods which you have declared in the body of the class. (Note that this is not possible in the case of Private classes (covered later)).

You can check out any one of these detailed tutorials on Classes and Objects in Python based on your preference -

* [Python Classes and Objects](https://www.learnpython.org/en/Classes_and_Objects)
* [Python Classes and Objects Detailed](https://www.programiz.com/python-programming/class)
Detailed Video Tutorials on Classes and Objects - [Video #1](https://www.youtube.com/watch?v=v_Jp11xqCzg&list=PLzMcBGfZo4-l1MqB1zoYfqzlj_HH-ZzXt&index=3) and [Video #2](https://www.youtube.com/watch?v=jQiUOV15IRI&list=PLzMcBGfZo4-l1MqB1zoYfqzlj_HH-ZzXt&index=3)


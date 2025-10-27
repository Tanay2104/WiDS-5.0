# WiDS 5.0
## Monte Carlo Simulations: From calculating area to Gambling in BlackJack


Welcome, everyone! This document will serve as our central hub for the project. Here you will find the weekly plan, learning resources, and assignments.

#### **The 5-Week Journey**

Our project is a structured journey designed to take you from a programming novice to the architect of a simple artificial intelligence.

*   **Week 1: The Toolbox:** Master the essential toolkit of Python and NumPy.
*   **Week 2: Monte Carlo Estimation:** Use simulation to estimate the area of complex shapes and build intuition.
*   **Week 3: RL Theory:** Learn the foundational concepts of agents, policies, and value functions.
*   **Week 4: Monte Carlo Prediction:** Build an engine to evaluate any strategy for the game of Blackjack.
*   **Week 5: Monte Carlo Control:** Empower an agent to learn the optimal strategy for Blackjack entirely on its own.

---

### **Week 1: The Toolbox - Python & NumPy Fundamentals**

**Objective:** By the end of this week, you will be comfortable with the basics of the Python language and the NumPy library. You will be able to write vectorized code to perform fast numerical operations and create simple visualizations.

#### **Part 1: Learning Resources**

Your goal this week is to go through these high-quality tutorials. You don't need to memorize everything, but focus on understanding the core concepts. We'll also provide a tutorial on git, which will be (forever) useful for version control.

*   **Python Basics (for those new to the language):**
    * **Tutorial:** ([FreeCodeCamp Tutorial video](https://www.youtube.com/watch?v=eWRfhZUzrAc))
    *   **Reference:** The Official Python Tutorial ([docs.python.org](https://docs.python.org/3/tutorial/index.html))

    *   **Focus on:** Get comfortable with basic syntax. Focus especially on the later parts such as Object Oriented Programming in Python.
    
*   **NumPy - The Core of Scientific Computing:**
    * **Tutorial** ([FreeCodeCamp Tutorial Video](https://www.youtube.com/watch?v=QUT1VHiLmmI&pp=ygUgbnVtcHkgdHV0b3JpYWwgZm9yIGJlZ2lubmVycyBmY2M%3D))
    *   **Resource:** NumPy: The absolute basics for beginners ([numpy.org](https://numpy.org/doc/stable/user/absolute_beginners.html))
    *   **Focus on:** What is a NumPy array? How do you create arrays? What is array indexing, slicing, and, most importantly, **vectorization**? This concept is the key to writing fast, modern data science code.

*   **Matplotlib - Our Visualization Tool:**
    * **Tutorial** ([FreeCodeCamp Tutorial Video](https://www.youtube.com/watch?v=3Xc3CA655Y4))
    *   **Resource:** Pyplot Tutorial ([matplotlib.org](https://matplotlib.org/stable/tutorials/pyplot.html))
    *   **Focus on:** How to make a simple `plt.plot()` and `plt.scatter()`. We only need the very basics for now.

#### **Part 3: Week 1 Assignment - The Vectorization Challenge**

This assignment is designed to give you a hands-on feel for the power of NumPy and to be your first deliverable for the project. Create a new Jupyter Notebook and follow the steps below.

**Objective:** Compare the speed of a standard Python `for` loop versus a vectorized NumPy operation for a common mathematical task.

1.  **Create Data:**
    *   Import the `numpy` and `time` libraries.
    *   Create two large, random NumPy arrays, `y_true` and `y_pred`, each with 1,000,000 elements.

2.  **Method 1: The `for` loop:**
    *   Write a Python function that calculates the Mean Squared Error (MSE) using a `for` loop to iterate through the elements of the arrays.
    *   Use the `%timeit` magic command in Jupyter to measure how long this function takes to run.

3.  **Method 2: Vectorized NumPy:**
    *   Write a single line of code that calculates the same MSE using only NumPy operations (hint: subtraction and `np.mean()`).
    *   Use the `%timeit` magic command to measure the execution time of this vectorized version.

4.  **Analysis:**
    *   In a Markdown cell at the end of your notebook, answer the following questions:
        *   "What was the speed difference you observed?"
        *   "Why do you think the NumPy version is so much faster?"

#### **Part 4: Submission**

Please submit your completed your python code by the end of the week. This will confirm you have your environment set up and are comfortable with the basics.

Good luck, and don't hesitate to ask questions

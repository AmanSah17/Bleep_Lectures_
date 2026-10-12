# Bleep Lecture 0: Python Programming Fundamentals

This repository contains beginner-friendly course material for learning Python through Jupyter notebooks. It includes guided lessons, focused practice notebooks, examples for working with modules and files, and a separate set of fundamentals exercises.

The materials are intended for classroom use and self-study. Work through the notebooks in order, run the examples, and change the code to explore how Python behaves.

## Learning objectives

By the end of these lessons, learners should be able to:

- Explain how Python code is written and executed.
- Use variables, built-in data types, operators, and type conversions.
- Work with strings and common collection types.
- Write conditional logic, loops, and reusable functions.
- Import and use modules.
- Read from and write to files using Python.
- Apply foundational concepts to short programming exercises.

## Getting started

### Requirements

- Python 3.
- Jupyter Notebook or JupyterLab.

The lessons use Python's standard library and do not require additional project packages.

### Install and launch Jupyter

If Jupyter is not installed in your Python environment, install it with:

```bash
python -m pip install notebook
```

From the repository directory, start the notebook server:

```bash
jupyter notebook
```

Alternatively, open the repository in JupyterLab. Select a notebook from `notebooks/` or `Exercise_section/` and run its cells from top to bottom. Some notebooks contain exercises; try solving them before viewing or changing any solution cells.

## Repository contents

### `notebooks/`

See [`notebooks/README.md`](notebooks/README.md) for the notebook index and a recommended learning sequence.

| Section | Notebook | Main topics |
| --- | --- | --- |
| 1a | [`02_1a_Python_Foundations_01.ipynb`](notebooks/02_1a_Python_Foundations_01.ipynb) | Python introduction, syntax, variables, and foundational examples |
| 1b | [`1b_Python_Foundations_02.ipynb`](notebooks/1b_Python_Foundations_02.ipynb) | Strings, lists, indexing, slicing, and related operations |
| 2a | [`1_Python_datatypes_and_functions.ipynb`](notebooks/1_Python_datatypes_and_functions.ipynb) | Python data types, collections, and functions |
| 2b | [`02b-Python Crash Course Exercises.ipynb`](notebooks/02b-Python%20Crash%20Course%20Exercises.ipynb) | Practice problems for introductory Python concepts |
| 2c | Not currently included | No modules lesson notebook is present in this repository |
| 2d | [`02d_Working_with_Files_in_Python.ipynb`](notebooks/02d_Working_with_Files_in_Python.ipynb) | Reading, writing, and managing files |
| 3a | [`03_1a_classes_&_methods_OOPS.ipynb`](notebooks/03_1a_classes_%26_methods_OOPS.ipynb) | Classes, methods, encapsulation, inheritance, polymorphism, and abstraction |
| 3b | [`03_1b_Object_Oriented_Python.ipynb`](notebooks/03_1b_Object_Oriented_Python.ipynb) | Objects, classes, attributes, methods, and class versus instance variables |

### `Exercise_section/`

Contains `Exercise_1_Python_Fundamentals_Exercise_Problems.ipynb`, a practice notebook covering variables, arithmetic, strings, slicing, conditions, loops, and basic logic. See [`Exercise_section/README.md`](Exercise_section/README.md) for guidance.

## Suggested learning sequence

1. Work through sections 1a and 1b for Python foundations, strings, and collections.
2. Continue with sections 2a and 2b for data types, functions, and practice.
3. Study section 2d for file operations. Section 2c is not currently included.
4. Continue with sections 3a and 3b to learn object-oriented programming.
5. Use [`1_Python_Programming_Fundamentals_Complete.ipynb`](notebooks/1_Python_Programming_Fundamentals_Complete.ipynb) or [`Python_Programming_Fundamentals_Complete.ipynb`](notebooks/Python_Programming_Fundamentals_Complete.ipynb) as broader fundamentals reviews, and practice with the notebook in `Exercise_section/`.

The notebooks can also be used independently as topic references.

## Lecture slides

[Open the Google Slides presentation](https://docs.google.com/presentation/d/13HJhHUI5IbTunlnvg4x2b14D6fnLBvagN9sCQKKGE7E/edit?usp=sharing).

## Working with notebooks

- Run cells in order so that variables and imports are defined before they are used.
- Restart the kernel and run all cells if results seem inconsistent.
- Save a personal copy before making changes to course examples.
- Notebook output is included where useful; rerunning a cell may produce different results when it reads input or interacts with files.

## License and use

These materials are provided for educational use in Python lectures, workshops, and self-study. Refer to the original course materials and repository terms when redistributing or adapting them.

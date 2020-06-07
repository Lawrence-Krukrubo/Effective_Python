# Effective_Python
**Intuitive and effective Python concepts and processes.**

This Repo explores Python Data structures. Their attributes, common use cases, methods and functions.
It contains a few Notebooks covering specific details about Python objects and processes.

## Structure:
This Repo contains Colab Notebooks that cover certain aspects of Python programming.

### Notebook 1: Intro_to_importing_data_in_python.ipynb
This notebook extensively covers best practices on importing Data into Python environment from various Data Files:
To follow along with these exercises kindly import the following libraries...

* `import numpy as np`
* `import pandas as pd`
* `import matplotlib.pyplot as plt`
* `import seaborn as sns`
* `import os`
* `import pickle`
* `! pip install sas7bdat`
* `from sas7bdat import SAS7BDAT`
* `! pip install h5py`
* `import h5py`
* `import scipy.io`
* `from sqlalchemy import create_engine`


**Notebook 1, covers the following topics extensively.**

* Reading text files.
* Importing flat files.
* Importing flat files using numpy.
* Working with mixed data types.
* Importing flat files in pandas Data Frames.
* Customizing pandas imports.
* Importing Excel files in pandas.
* Importing Excel sheets by name
* importing Excel sheets by index.
* Customising Excel imports.
* Importing SAS files.
* Importing Stata files 
* Importing HDF5 files.
* Importing MATLAB files
* Subsetting the .mat object.
* Loading Pickled data files.
* Loading and importing Parquet files.

#### Section Two:
* Working with relational data bases in Python.
* Customising SQL queries.
* Filtering Database records using SQL `where`.
* Ordering SQL records using `orderby`.
* Querying Relational Databases directly with pandas.
* Advanced Querying: Exploiting table relationships.
* Filtering by `joins'.


### Notebook 2: Python List Comprehensions and Generators
List comprehensions are not limited to only lists.
We can write a list comprehension on any iterable, such as range() and tuples and even dictionaries.
List comprehensions collapse for loops for building lists into a single line.
We can also use list comprehnsions in place of nested for loops.

To follow along with these exercises, we need the following module:-
* `! pip install python`

**Components of a list comprehension are:**

* An iterable
* An iterator variable(representing members of an iterable)
* Output Expression

**Notebook 2, explains further details about the following Python concepts:-**

* Using a list comprehension instead of a nested for loop
* Nested List Comprehensions
* Advanced Comprehensions:
  * Conditionals in Comprehensions
  * Dictionary Comprehensions
* Introduction to Generator Expressions
* Generator Functions

### Blog_Post:
For more details about this repo, including a further explanation of the concepts in the Notebooks, kindly see links below:-

* [Loading Different Data Files in Python](https://medium.com/p/b6385320c0f5/edit)
* [Effective Pandas: Using Chuksize for Large Datasets](https://medium.com/towards-artificial-intelligence/efficient-pandas-using-chunksize-for-large-data-sets-c66bf3037f93)

### License:
The entire repo and all files and data abide under the MIT License attached in the root directory above.

# Data-Analysis-Tools

### Author: [Samrat Mitra](https://www.github.com/lionelsamrat10)

A data scientist must be a good data analyzer also. This repository contains Jupyter Notebooks for all the tools one need to perform Data Analysis such that Numpy, Pandas, Matplotlib, Seaborn and also some sample case studies are also included. We have included Exploratory Data Analysis on very famous datasets like the IPL Matches Dataset, Superheroes Dataset, FIFA Players Dataset from Kaggle and also Iris Dataset by University Of California, Irvine Machine Learning Repository.

## Numpy
![Numpy](https://user-images.githubusercontent.com/1217238/65354639-dd928f80-dba4-11e9-833b-bc3e8c6a737d.png)

[Notebook Available here](https://github.com/lionelsamrat10/Data-Analysis-Tools/blob/main/Numpy/Numpy%20complete%20Tutorial.ipynb)

<p>
NumPy is the fundamental package for scientific computing in Python. It is a Python library that provides a multidimensional array object, various derived objects (such as masked arrays and matrices), and an assortment of routines for fast operations on arrays, including mathematical, logical, shape manipulation, sorting, selecting, I/O, discrete Fourier transforms, basic linear algebra, basic statistical operations, random simulation and much more.
</p>

### What is NumPy?

At the core of the NumPy package, is the ndarray object. This encapsulates n-dimensional arrays of homogeneous data types, with many operations being performed in compiled code for performance. There are several important differences between NumPy arrays and the standard Python sequences:

* NumPy arrays have a fixed size at creation, unlike Python lists (which can grow dynamically). Changing the size of an ndarray will create a new array and delete the original.

* The elements in a NumPy array are all required to be of the same data type, and thus will be the same size in memory. The exception: one can have arrays of (Python, including NumPy) objects, thereby allowing for arrays of different sized elements.

* NumPy arrays facilitate advanced mathematical and other types of operations on large numbers of data. Typically, such operations are executed more efficiently and with less code than is possible using Python’s built-in sequences.

* A growing plethora of scientific and mathematical Python-based packages are using NumPy arrays; though these typically support Python-sequence input, they convert such input to NumPy arrays prior to processing, and they often output NumPy arrays. In other words, in order to efficiently use much (perhaps even most) of today’s scientific/mathematical Python-based software, just knowing how to use Python’s built-in sequence types is insufficient - one also needs to know how to use NumPy arrays.

### Why is NumPy Fast?

Vectorization describes the absence of any explicit looping, indexing, etc., in the code - these things are taking place, of course, just “behind the scenes” in optimized, pre-compiled C code. Vectorized code has many advantages, among which are:

* vectorized code is more concise and easier to read

* fewer lines of code generally means fewer bugs

* the code more closely resembles standard mathematical notation (making it easier, typically, to correctly code mathematical constructs)

* vectorization results in more “Pythonic” code. Without vectorization, our code would be littered with inefficient and difficult to read for loops.

Broadcasting is the term used to describe the implicit element-by-element behavior of operations; generally speaking, in NumPy all operations, not just arithmetic operations, but logical, bit-wise, functional, etc., behave in this implicit element-by-element fashion, i.e., they broadcast. Moreover, in the example above, a and b could be multidimensional arrays of the same shape, or a scalar and an array, or even two arrays of with different shapes, provided that the smaller array is “expandable” to the shape of the larger in such a way that the resulting broadcast is unambiguous. For detailed “rules” of broadcasting see basics.broadcasting.

## Pandas

![Pandas](https://raw.githubusercontent.com/lionelsamrat10/Data-Analysis-Tools/main/Images/pandas.png)

[Notebook Available here](https://github.com/lionelsamrat10/Data-Analysis-Tools/blob/main/Pandas/Pandas%20Tutorial.ipynb)

Pandas is a software library written for the Python programming language for data manipulation and analysis. In particular, it offers data structures and operations for manipulating numerical tables and time series. It is free software released under the three-clause BSD license. The name is derived from the term "panel data", an econometrics term for data sets that include observations over multiple time periods for the same individuals. Its name is a play on the phrase "Python data analysis" itself. Wes McKinney started building what would become pandas at AQR Capital while he was a researcher there from 2007 to 2010.

### Library features

* DataFrame object for data manipulation with integrated indexing.
* Tools for reading and writing data between in-memory data structures and different file formats.
* Data alignment and integrated handling of missing data.
* Reshaping and pivoting of data sets.
* Label-based slicing, fancy indexing, and subsetting of large data sets.
* Data structure column insertion and deletion.
* Group by engine allowing split-apply-combine operations on data sets.
* Data set merging and joining.
* Hierarchical axis indexing to work with high-dimensional data in a lower-dimensional data structure.
* Time series-functionality: Date range generation[6] and frequency conversions, moving window statistics, moving window linear regressions, date shifting and lagging.
* Provides data filtration.
* The library is highly optimized for performance, with critical code paths written in Cython or C.

### Dataframes (Most Important Data Structure in Pandas)

Pandas is mainly used for data analysis. Pandas allows importing data from various file formats such as comma-separated values, JSON, SQL database tables or queries, and Microsoft Excel. Pandas allows various data manipulation operations such as merging, reshaping, selecting, as well as data cleaning, and data wrangling features.

## Maplotlib

![Matplotlib](https://raw.githubusercontent.com/lionelsamrat10/Data-Analysis-Tools/main/Images/matplotlib.jpg)

[Notebook Available here](https://github.com/lionelsamrat10/Data-Analysis-Tools/blob/main/Matplotlib/Matplotlib%20Tutorial.ipynb)

Matplotlib is a plotting library for the Python programming language and its numerical mathematics extension NumPy. It provides an object-oriented API for embedding plots into applications using general-purpose GUI toolkits like Tkinter, wxPython, Qt, or GTK. There is also a procedural "pylab" interface based on a state machine (like OpenGL), designed to closely resemble that of MATLAB, though its use is discouraged. SciPy makes use of Matplotlib.

Matplotlib was originally written by John D. Hunter. Since then it has an active development community and is distributed under a BSD-style license. Michael Droettboom was nominated as matplotlib's lead developer shortly before John Hunter's death in August 2012 and was further joined by Thomas Caswell. Matplotlib is a NumFOCUS fiscally sponsored project.

Matplotlib 2.0.x supports Python versions 2.7 through 3.10. Python 3 support started with Matplotlib 1.2. Matplotlib 1.4 is the last version to support Python 2.6. Matplotlib has pledged not to support Python 2 past 2020 by signing the Python 3 Statement.

### Toolkits

Several toolkits are available which extend Matplotlib functionality. Some are separate downloads, others ship with the Matplotlib source code but have external dependencies.

* **Basemap**: map plotting with various map projections, coastlines, and political boundaries
* **Cartopy**: a mapping library featuring object-oriented map projection definitions, and arbitrary point, line, polygon and image transformation capabilities. (Matplotlib v1.2 and above)
* **Excel tools**: utilities for exchanging data with Microsoft Excel
* **GTK tools**: interface to the GTK library
* **Qt interface**
* **Mplot3d**: 3-D plots
* **Natgrid**: interface to the natgrid library for gridding irregularly spaced data.
* **matplotlib2tikz**: export to Pgfplots for smooth integration into LaTeX documents
* **Seaborn**: provides an API on top of Matplotlib that offers sane choices for plot style and color defaults, defines simple high-level functions for common statistical plot types, and integrates with the functionality provided by Pandas


## Seaborn
![Seaborn](https://github.com/lionelsamrat10/Data-Analysis-Tools/blob/main/Images/seaborn.svg)

[Notebook Available here](https://github.com/lionelsamrat10/Data-Analysis-Tools/blob/main/Seaborn/Seaborn%20Tutorial.ipynb)

Seaborn is a library for making statistical graphics in Python. It builds on top of matplotlib and integrates closely with pandas data structures.

Seaborn helps you explore and understand your data. Its plotting functions operate on dataframes and arrays containing whole datasets and internally perform the necessary semantic mapping and statistical aggregation to produce informative plots. Its dataset-oriented, declarative API lets you focus on what the different elements of your plots mean, rather than on the details of how to draw them.


## Exploratory Data Analysis Case Studies

|Serial Number| Project Name      | Link |
| ----------- | ----------- | ----------- |
|1.| Iris Dataset EDA      | [Iris EDA](https://github.com/lionelsamrat10/Data-Analysis-Tools/blob/main/Exploratory%20Data%20Analysis%20Projects/Iris%20EDA/EDA%20on%20Iris%20Dataset.ipynb)      |
|2.| IPL Matches Dataset EDA   | [IPL EDA](https://github.com/lionelsamrat10/Data-Analysis-Tools/blob/main/Exploratory%20Data%20Analysis%20Projects/IPL%20Dataset%20EDA/IPL%20Exploratory%20Data%20Analysis.ipynb)       |
|3.| FIFA Players Dataset EDA   | [FIFA EDA](https://github.com/lionelsamrat10/Data-Analysis-Tools/blob/main/Exploratory%20Data%20Analysis%20Projects/FIFA%2020%20Dataset%20EDA/FIFA%2020%20EDA%20Notebook.ipynb)        |
|4.| Superheroes Dataset EDA   | [Superheroes EDA](https://github.com/lionelsamrat10/Data-Analysis-Tools/blob/main/Exploratory%20Data%20Analysis%20Projects/Marvel%20Avengers%20Dataset%20EDA/Superheroes%20Dataset%20EDA.ipynb)       |

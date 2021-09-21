# Amazon_seller_sales_Data_Analysis

# NumPy 

NumPy (or Numpy) is a Linear Algebra Library for Python, the reason it is so important for Data Science with Python is that almost all of the libraries in the PyData Ecosystem rely on NumPy as one of their main building blocks.

Numpy is also incredibly fast, as it has bindings to C libraries. For more info on why you would want to use Arrays instead of lists, check out this great [StackOverflow post](http://stackoverflow.com/questions/993984/why-numpy-instead-of-python-lists).

We will only learn the basics of NumPy, to get started we need to install it!

## Installation Instructions

**It is highly recommended you install Python using the Anaconda distribution to make sure all underlying dependencies (such as Linear Algebra libraries) all sync up with the use of a conda install. If you have Anaconda, install NumPy by going to your terminal or command prompt and typing:**
    
    conda install numpy
    
**If you do not have Anaconda and can not install it, please refer to [Numpy's official documentation on various installation instructions.](http://docs.scipy.org/doc/numpy-1.10.1/user/install.html)**

# Introduction to Pandas

In this section of the course we will learn how to use pandas for data analysis. You can think of pandas as an extremely powerful version of Excel, with a lot more features. In this section of the course, you should go through the notebooks in this order:

* Introduction to Pandas
* Series
* DataFrames
* Missing Data
* GroupBy
* Merging,Joining,and Concatenating
* Operations

# Matplotlib

Matplotlib is one of the most popular Python packages used for data visualization. It is a cross-platform library for making 2D plots from data in arrays. It provides an object-oriented API that helps in embedding plots in applications using Python GUI toolkits such as PyQt, WxPythonotTkinter. It can be used in Python and IPython shells, Jupyter notebook and web application servers also.


Matplotlib is written in Python and makes use of NumPy, the numerical mathematics extension of Python. We assume that the readers of this tutorial have basic knowledge of Python.

# Downloading Amazon Order History Data
Amazon allows you to download pretty extensive reports on the orders you’ve made, although the available data only dates back to 2006. Still, if you’re a regular Amazon user, more than a decade of data is likely to contain some interesting insights!

To get the data, clicking on this link while logged in should take us directly to the order reports download page. But if that doesn’t work, we can also navigate to that page directly: go to Amazon.com and click the Accounts and Lists button in the top right. On the next page, look for the Ordering and Shopping Preferences section, and click on the link under that heading that says “Download order reports”.

If you’d like to work through this tutorial but would prefer not to use your own data, you can download the same anonymized data set we’re using for this tutorial.

Amazon offers four different report types. For now, we’re going to download an Orders and shipments report, so select that option from the drop-down menu. Then, we can choose a start date and end date for the data we’d like to look at. To see all of Amazon’s stored data, we’ll need to set the Start Date to January 1, 2006. Then, we can click the little “Use today” button next to the End Date to automatically fill in today’s date

Once everything is ready, click “Request Report” and Amazon will begin building the report for you.

We’re almost ready to dive into a little programming and do our analysis. But first, let’s make things a little easier by renaming and moving that file we just downloaded. By default, this will probably be called something like 01_Jan_2006_to_10_Sept_2019.csv, but let’s rename it something simpler: amazon-orders.csv.

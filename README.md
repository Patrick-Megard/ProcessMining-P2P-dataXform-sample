# Procure To Pay Multilevel process data transformation

In this example, we are going to transform a few data files provided by a client, into a multi-level process event-log that can be loaded and analyzed in IBM Process Mining.

This data transformation process can be done using various techniques and tools, and it is really a strength that clients can apply their existing data practices and skills to feed IBM Process Mining.

The exact same transformation process is also illustrated in another lab using IBM SPSS. We could be using IBM Datastage, Talend, and so forth.

The goal of this example is to show how easy it is to do this work using Python language and Pandas library. Obviously, basic programming skills are required, but you will see that handling tables with Pandas (called dataframes) is quite simple, and that you can reuse parts of this example in your own project.

Installing and running Jupyterlab
You need to have Python installed to run Jupyterlab locally. These steps should be sufficient to install Python and pandas on a Linux host:

> yum install -y python36-devel.x86_64

> pip3 install jupyterlab

> pip3 install pandas

Then run:

> jupyter lab --allow-root

Similar instructions exist for installing on Mac or Windows.

## What is Pandas
Pandas is an open source Python package that is most widely used for data science/data analysis and machine learning tasks. It is built on top of another package named Numpy, which provides support for multi-dimensional arrays. As one of the most popular data wrangling packages, Pandas works well with many other data science modules inside the Python ecosystem, and is typically included in every Python distribution.

## Python
The Python code is using Pandas to manipulate the dataframes. It contains all the needed explanations [Code](P2P_dataxform_lab.ipynb)

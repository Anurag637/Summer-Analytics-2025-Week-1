# Summer-Analytics-2025-Week-1
Consistent Car Models Analysis
Overview
This project analyzes a dataset of cars to identify consistent car models — defined as models produced over multiple years with very low variation in miles per gallon (MPG). The goal is to find car models with stable fuel efficiency across their production years.

Dataset
The dataset (Cars.csv) contains details about cars, including:

MPG (miles per gallon)

Cylinders

Displacement

Horsepower

Weight

Acceleration

Model year

Origin

Car name

Objective
Identify car models that:

Appear in at least two different model years.

Have a standard deviation of MPG less than 1.0 across those years.

For these models, report:

Model name

Number of years produced (appearances)

Average MPG

Usage
The analysis is performed using Python with libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

The key code block for identifying consistent models is provided.

You can run the code in any Python environment (Jupyter notebook, script, etc.).

Results
The output lists consistent car models, their production span (in years), and average fuel efficiency.

This insight helps identify stable performers in fuel economy over time.

Dependencies
Python 3.x

Pandas

NumPy

Matplotlib

Seaborn

# Python-Week-7-Assignment
📘 Assignment: Analyzing Data with Pandas and Visualizing Results with Matplotlib
Objective

The purpose of this assignment is to:

Load and analyze a dataset using the pandas library in Python.

Perform basic exploratory data analysis (EDA).

Create and customize visualizations using matplotlib (and seaborn for styling).

Dataset Used

Iris Dataset (from sklearn.datasets)

This is a classic dataset commonly used in machine learning and data science.

It contains 150 samples of iris flowers, with the following features:

Sepal length (cm)

Sepal width (cm)

Petal length (cm)

Petal width (cm)

Species (Setosa, Versicolor, Virginica)

Project Structure

The project is organized into three main tasks:

Task 1: Load and Explore the Dataset

The dataset is loaded using sklearn.datasets.load_iris.

Converted into a pandas DataFrame for easier analysis.

Inspected the first few rows using .head().

Checked data types and missing values with .info() and .isnull().

Cleaned the dataset (dropped missing values if any).

Task 2: Basic Data Analysis

Computed summary statistics using .describe().

Grouped the dataset by species and calculated the mean values for each numeric feature.

Key findings:

Setosa flowers have the smallest petals.

Virginica flowers generally have the largest sepals and petals.

Versicolor flowers lie between the two in size.

Task 3: Data Visualization

Created four types of visualizations to better understand the dataset:

Line Chart – Shows the trend of petal length across samples.

Bar Chart – Compares the average petal length across species.

Histogram – Displays the distribution of sepal length values.

Scatter Plot – Visualizes the relationship between sepal length and petal length, colored by species.

Each chart is customized with titles, axis labels, and legends for clarity.

Technologies and Libraries Used

Python 3.x

pandas → data loading, cleaning, and analysis.

matplotlib → plotting and customization.

seaborn → improved plotting style and aesthetics.

scikit-learn → to load the Iris dataset.
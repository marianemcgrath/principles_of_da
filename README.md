# Principles of Data Analytics

by Mariane McGrath
# Overview
This Jupyter Notebook contains practical exercises and code implementations for fundamental data analysis concepts. It serves as a hands-on companion to theoretical principles and covers essential data manipulation, visualisation, and analysis techniques.

The Iris dataset is a classic dataset in machine learning and statistics. It contains 150 records of iris flowers, divided into three species:
1. Setosa
2. Versicolor
3. Virginica

Each record contains the following features:
 - sepal length (cm)
 - sepal width (cm)
 - petal length (cm)
 - petal width (cm)
 - species (target class)
   
Source: https://www.geeksforgeeks.org/iris-dataset/

## Dependencies
To run this notebook, you'll need:
 - Python 3.6+
 - Jupyter Notebook/Lab
 - Git/GitHub
 - Codespaces

Required Python packages: See requirements.txt

Install dependencies with:
 - pip install pandas numpy matplotlib seaborn scipy jupyter

## Usage Instructions
1. Clone the repository:
 - git clone https://github.com/marianemcgrath/principles_of_da.git
2. Navigate to the repository directory
3. Launch Jupyter Notebook
4. Open tasks.ipynb from the file browser

## Table of Contents
- [Overview](#overview)
- [Table of Contents](#table-of-contents)
  - [Task 1](#task-1)
  - [Task 2](#task-2)
  - [Task 3](#task-3)
  - [Task 4](#task-4)
  - [Task 5](#task-5)
  - [Task 6](#task-6)
  - [Task 7](#task-7)
  - [Task 8](#task-8)
  - [Task 9](#task-9)
  - [Task 10](#task-10)
- [Dependencies](#dependencies)
- [Usage Instructions](#usage-instructions)
- [Key Features](#key-features)
- [Resources](#resources)
- [Contact](#contact)
- [License](#license)

# Key Features
 - Interactive Code Cells: All code is executable and can be modified
 - Commented Code: Major steps include explanatory comments
 - Progressive Difficulty: Tasks build from basic to advanced concepts

## Table of Contents
The notebook is organised into clear sections, each focusing on a specific data analysis task or concept.

### Task 1
- Sourcing the Data Set: Import the Iris data set from the sklearn.datasets module. Explain, in your own words, what the load_iris() function returns.
### Task 2
- Exploring the Data Structure: Print and explain the shape of the data set, the first and last 5 rows of the data, the feature names, and the target classes.
### Task 3
- Summarising the Data: For each feature in the dataset, calculate and display: mean, minimum, maximum, standard deviation, median
### Task 4
- Visualising Features: Plot histograms for each feature using matplotlib. Add appropriate titles and axis labels.
### Task 5
- Investigating Relationships: Choose any two features from the data set and create a scatter plot of them. Colour-code the three different classes of the scatter plot points.
### Task 6
- Analysing Class Distributions: Use numpy.polyfit to add a regression line to the scatter plot from Task 5.
### Task 7
- Boxplots of Petal lengths: Create box-plots of the petal lengths for each of the three classes.
### Task 8
- Correlation Heatmap: Calculate the correlation coefficients between the features. Display the results as a heatmap using matplotlib.
### Task 9
 - Fit a Simple Linear Regression: For your two features in Task 5, calculate the coefficient of determination R^2. Re-create the plot from Task 6 and annotate it with the R^2 value.
### Task 10
- Pairplot of the dataset: Use seaborn to create a pairplot of the dataset. Explain, in your own words, what the pairplot depicts.

# Resources



# Contact
 - Mariane McGrath
 - Email: G00473468@atu.ie
 - LinkedIn: /marianemcgrath
   
Feel free to reach out with questions or feedback!

## License 
This project is for educational purposes as part of the Programming and Scripting course at ATU. Feel free to reference or adapt, but please avoid plagiarism.

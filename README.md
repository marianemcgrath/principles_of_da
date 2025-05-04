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
The tasks required to be completed are as follows:

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

 **Datasets & Tools:**
 - Iris Dataset
 - UCI Machine Learning Repository: https://archive.ics.uci.edu/dataset/53/iris
 - Scikit-learn Documentation: https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_iris.html

**Python Libraries:**
 - NumPy: https://numpy.org/doc/stable/user/whatisnumpy.html
 - SciPy: https://scipy.org/
 - Scikit-learn Tutorial: https://www.digitalocean.com/community/tutorials/python-scikit-learn-tutorial

**Jupyter Setup:**
 - BMC Guide: https://www.bmc.com/blogs/installing-jupyter-for-big-data-and-analytics/
 - Data Handling & Analysis

**Pandas & DataFrames:**
 - Converting Datasets: https://stackoverflow.com/questions/38105539/how-to-convert-a-scikit-learn-dataset-to-a-pandas-dataset

  head(), tail(), and shape:
 - GeeksforGeeks: https://www.geeksforgeeks.org/how-to-print-the-first-or-last-rows-of-a-data-set/
 - Medium: https://medium.com/@heyamit10/understanding-pandas-shape-ba74dadf8387
 - Analytics Vidhya: https://www.analyticsvidhya.com/blog/2023/07/head-and-tail-functions/
 - DataFrame Size: https://www.datacamp.com/tutorial/python-dataframe-size
 - Descriptive Stats (describe()): https://www.w3schools.com/python/pandas/ref_df_describe.asp

**Statistical Metrics:**
 - Mean/Standard Deviation:
  - UCD: https://www.ucd.ie/msc/t4media/Mean%20and%20Standard%20Deviation.pdf
  - LibreTexts: https://eng.libretexts.org/Bookshelves/Industrial_and_Systems_Engineering/Chemical_Process_Dynamics_and_Controls_(Woolf)/13%3A_Statistics_and_Probability_Background/13.01%3A_Basic_statistics-_mean_median_average_standard_deviation_z-scores_and_p-value

**Data Visualization**
 - General Visualization
  - Benefits:
 - Deloitte: https://www.deloitte.com/nl/en/services/tax/perspectives/bps-the-five-benefits-of-data-visualization.html
 - Tableau: https://www.tableau.com/visualization/what-is-data-visualization

**Matplotlib & Seaborn:**
 - Intro to Matplotlib: https://www.w3schools.com/python/matplotlib_intro.asp
 - Histograms: https://flexiple.com/python/exploratory-data-analysis-on-iris-dataset

**Scatter Plots:**
 - Scikit-learn: https://scikit-learn.org/1.4/auto_examples/datasets/plot_iris_dataset.html
 - Medium (Zion Oladiran): https://zion-oladiran.medium.com/exploratory-data-analysis-iris-dataset-68897497b120

**Boxplots:**
 - Chartio: https://chartio.com/resources/tutorials/what-is-a-box-plot/
 - Tableau: https://www.tableau.com/chart/what-is-box-and-whisker-plot
 - GeeksforGeeks: https://www.geeksforgeeks.org/box-plot-in-python-using-matplotlib/

**Heatmaps:**
 - GeeksforGeeks: https://www.geeksforgeeks.org/generate-a-heatmap-in-matplotlib-using-a-scatter-dataset
 - Matplotlib: https://matplotlib.org/stable/gallery/images_contours_and_fields/image_annotated_heatmap.html
 - Atlassian Guide: https://www.atlassian.com/data/charts/heatmap-complete-guide

**Pair Plots**
 - Analytics Vidhya: https://www.analyticsvidhya.com/blog/2024/02/pair-plots-in-machine-learning/
 - YouTube (Iris Classification): https://www.youtube.com/watch?v=dlFScQLOtoY

**Regression & Correlation**
 - Linear Regression:
   - StackOverflow (Formula): https://stackoverflow.com/questions/55696942/how-to-apply-y-mx-b-formula-in-python
   - Kaggle (Iris Regression): https://www.kaggle.com/code/lampubhutia/iris-linear-regression

**R-squared Explanation:**
 - Newcastle University: https://www.ncl.ac.uk/webtemplate/ask-assets/external/maths-resources/statistics/regression-and-correlation/coefficient-of-determination-r-squared
 - SciPy: https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.linregress.html

**Additional Resources**
 - Scikit-learn: https://scikit-learn.org/stable/auto_examples/decomposition/plot_pca_iris.html
 - Copilot: Used for graph styling assistance.


# Contact
 - Mariane McGrath
 - Email: G00473468@atu.ie
 - LinkedIn: /marianemcgrath
   
Feel free to reach out with questions or feedback!

## License 
This project is for educational purposes as part of the Programming and Scripting course at ATU. Feel free to reference or adapt, but please avoid plagiarism.

# MSDS 610 Code Demo
# Topic: EDA
As data scientists, we make good use of data. To do so, however, requires more than just following a paved road since every data set needs a different approach. We need to look at the data before making any assumptions or deciding what to do with it. That’s why we study exploratory data analysis, or EDA. It is all about making sense of the data in our hands, before getting them dirty with it. This process helps maximize insight into a data set using a variety of techniques (mostly graphical). We can uncover underlying structure, identify obvious errors, patterns, outliers, find interesting relations among the variables, extract important variables, etc. We use EDA to ensure the results we produce are valid and applicable to any desired business outcomes and goals.

We have performed some EDA tasks on the 'Avocado' dataset found on Kaggle (https://www.kaggle.com/datasets/neuromusic/avocado-prices?resource=download) for illustration. The written Python code can be found in 'avocado.ipynb' file in this repository. Here we will briefly describe the process.

After taking an initial look at the data set, we would like to answer the following questions:
1. Is there any difference between the price of organic avocados and that of conventional ones?
2. Is the sales volume of avocado correlated to its average price?
3. Which regions in the U.S consume the most avocados?
4. How does avocado price vary by regions?

Here is a summary of the tasks done in the example:
1. Data Import

2. Initial Sniff on the Data Set (Assumptions Check and Data Clean-up)
  - Summary (check missing values and data types)
  - Check column names and drop unnecessary ones
  - Check data range
  - Correct data type if needed
  - Check data balance
  - Check data distribution

3. Data Visualization
  - Example 1 : Bar Chart
  - Example 2 : Histogram
  - Example 3 : Box-Whisker Plot
  - Example 4 : Line Plot
  - Example 5 : Word Cloud
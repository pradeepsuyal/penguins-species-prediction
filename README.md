### penguins species prediction using random forest

![penguin](https://user-images.githubusercontent.com/86251750/145684368-de440a6f-ad7a-4b4a-b9b3-f902cb49eca1.jpg)

## Table of CONTENTS 
---------------------
 * [Aim](#aim)
 * [Dataset used](#data)
 * [Exploring the Data](#viz)
   - [Matplotlib](#matplotlib)
   - [Seaborn](#seaborn)
 * [using RandomForest](#conclusion)
 

## AIM:<a name="aim"></a>

Our goal is to create a model that can help predict a species of a penguin based on physical attributes, then we can use that model to help researchers classify penguins in the field, instead of needing an experienced biologist

## Dataset Used:<a name="data"></a>

We will be using the same dataset through our discussions on classification with tree-methods (Decision Tree,Random Forests, and Gradient Boosted Trees) in order to compare performance metrics across these related models.

We will work with the "Palmer Penguins" dataset, as it is simple enough to help us fully understand how changing hyperparameters can change classification results.

Data were collected and made available by Dr. Kristen Gorman and the Palmer Station, Antarctica LTER, a member of the Long Term Ecological Research Network.

Gorman KB, Williams TD, Fraser WR (2014) Ecological Sexual Dimorphism and Environmental Variability within a Community of Antarctic Penguins (Genus Pygoscelis). PLoS ONE 9(3): e90081. doi:10.1371/journal.pone.0090081

Summary: The data folder contains two CSV files. For intro courses/examples, you probably want to use the first one (penguins_size.csv).

penguins_size.csv: Simplified data from original penguin data sets. Contains variables:

* species: penguin species (Chinstrap, Adélie, or Gentoo)

* culmen_length_mm: culmen length (mm)

* culmen_depth_mm: culmen depth (mm)

* flipper_length_mm: flipper length (mm)

* body_mass_g: body mass (g)

* island: island name (Dream, Torgersen, or Biscoe) in the Palmer Archipelago (Antarctica)

* sex: penguin sex

(Not used) penguins_lter.csv: Original combined data for 3 penguin species

    Note: The culmen is "the upper ridge of a bird's beak"

## Exploring the Data:<a name="viz"></a>

Here I will use pandas and seaborn visualization skills to determine if Fandango's ratings in 2015 had a bias towards rating movies better to sell more tickets.

**Matplotlib:**<a name="matplotlib"></a>
--------
Matplotlib is a Python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments across platforms. Matplotlib can be used in Python scripts, the Python and IPython shells, the Jupyter notebook, web application servers, and four graphical user interface toolkits.You can draw up all sorts of charts(such as Bar Graph, Pie Chart, Box Plot, Histogram. Subplots ,Scatter Plot and many more) and visualization using matplotlib.

Environment Setup==
If you have Python and Anaconda installed on your computer, you can use any of the methods below to install matplotlib:

     pip: pip install matplotlib

     anaconda: conda install matplotlib
     
     import matplotlib.pyplot as plt

for more information you can refer to [matplotlib](https://matplotlib.org/) official site

**Seaborn:**<a name="seaborn"></a>
------
Seaborn is built on top of Python’s core visualization library Matplotlib. Seaborn comes with some very important features that make it easy to use. Some of these features are:

**Visualizing univariate and bivariate data.**

**Fitting and visualizing linear regression models.**

**Plotting statistical time series data.**

**Seaborn works well with NumPy and Pandas data structures**

**Built-in themes for styling Matplotlib graphics**

**The knowledge of Matplotlib is recommended to tweak Seaborn’s default plots.**

Environment Setup==
If you have Python and Anaconda installed on your computer, you can use any of the methods below to install seaborn:

    pip: "pip install seaborn"*

    anaconda: " conda install seaborn"*
    import seaborn as sns
    
for more information you can refer to [seaborn](https://seaborn.pydata.org/) official site.


## using RandomForest for prediction:<a name="conclusion"></a>

Random forest is a type of supervised learning algorithm that uses ensemble methods (bagging) to solve both regression and classification problems. The algorithm operates by constructing a multitude of decision trees at training time and outputting the mean/mode of prediction of the individual trees.

The fundamental concept behind random forest is the wisdom of crowds wherein a large number of uncorrelated models operating as a committee will outperform any of the individual constituent models.

The reason behind this is the fact that the trees protect each other from their individual errors. Within a random forest, there is no interaction between the individual trees. A random forest acts as an estimator algorithm that aggregates the result of many decision trees and then outputs the most optimal result.

![randomforest](https://miro.medium.com/max/480/1*w-b0xHDoUsCcwx4nY3x5Og.gif)

**Evaluation with confusion matrix**

![22](https://user-images.githubusercontent.com/86251750/145684772-e9cdd3bf-46f1-49da-bcf9-42b883684887.PNG)

***language used***
--------------------------
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

**Tools**
-----------------------
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)    ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)   ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)  ![Made with matplotlib](https://user-images.githubusercontent.com/86251750/132984208-76ce70c7-816d-4f72-9c9f-90073a70310f.png)  ![seaborn](https://user-images.githubusercontent.com/86251750/132984253-32c04192-989f-4ebd-8c46-8ad1a194a492.png)


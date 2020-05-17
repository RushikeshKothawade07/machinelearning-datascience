# Complete Machine Learning and Data Science: Zero to Mastery (2020)

## Table of Contents

- [Complete Machine Learning and Data Science: Zero to Mastery (2020)](#complete-machine-learning-and-data-science-zero-to-mastery-2020)
  - [Table of Contents](#table-of-contents)
  - [**Section 2: Machine Learning 101**](#section-2-machine-learning-101)
    - [What Is Machine Learning?](#what-is-machine-learning)
    - [AI/Machine Learning/Data Science](#aimachine-learningdata-science)
    - [How Did We Get Here?](#how-did-we-get-here)
    - [Types of Machine Learning](#types-of-machine-learning)
    - [What Is Machine Learning? Round 2](#what-is-machine-learning-round-2)
  - [**Section 3: Machine Learning and Data Science Framework**](#section-3-machine-learning-and-data-science-framework)
    - [Introducing Our Framework](#introducing-our-framework)
    - [6 Step Machine Learning Framework](#6-step-machine-learning-framework)
    - [Types of Machine Learning Problems](#types-of-machine-learning-problems)
    - [Types of Data: What kind of data do we have?](#types-of-data-what-kind-of-data-do-we-have)
    - [Types of Evaluation: What defines success for us?](#types-of-evaluation-what-defines-success-for-us)
    - [Features In Data: What do we already know about the data?](#features-in-data-what-do-we-already-know-about-the-data)
    - [Modelling Part 1 - 3 sets](#modelling-part-1---3-sets)
    - [Modelling Part 2 - Choosing](#modelling-part-2---choosing)
    - [Modelling Part 3 - Tuning](#modelling-part-3---tuning)
    - [Modelling Part 4 - Comparison](#modelling-part-4---comparison)
    - [Experimentation](#experimentation)
    - [Tools We Will Use](#tools-we-will-use)
  - [**Section 4: The 2 Paths**](#section-4-the-2-paths)
  - [**Section 5: Data Science Environment Setup**](#section-5-data-science-environment-setup)
    - [Introducing Our Tools](#introducing-our-tools)
    - [What is Conda?](#what-is-conda)
    - [Conda Environments](#conda-environments)
    - [Mac Environment Setup](#mac-environment-setup)
    - [Mac Environment Setup 2](#mac-environment-setup-2)
    - [Sharing your Conda Environment](#sharing-your-conda-environment)
    - [Jupyter Notebook Walkthrough](#jupyter-notebook-walkthrough)
  - [**Section 6: Pandas: Data Analysis**](#section-6-pandas-data-analysis)
    - [Pandas Introduction](#pandas-introduction)
    - [Series, Data Frames and CSVs](#series-data-frames-and-csvs)
    - [Data from URLs](#data-from-urls)
    - [Describing Data with Pandas](#describing-data-with-pandas)
    - [Selecting and Viewing Data with Pandas](#selecting-and-viewing-data-with-pandas)
    - [Manipulating Data](#manipulating-data)
    - [Assignment: Pandas Practice](#assignment-pandas-practice)
  - [**Section 7: NumPy**](#section-7-numpy)
    - [Section Overview](#section-overview)
    - [NumPy Introduction](#numpy-introduction)
    - [NumPy DataTypes and Attributes](#numpy-datatypes-and-attributes)
    - [Creating NumPy Arrays](#creating-numpy-arrays)
    - [NumPy Random Seed](#numpy-random-seed)
    - [Viewing Arrays and Matrices](#viewing-arrays-and-matrices)
    - [Manipulating Arrays](#manipulating-arrays)
    - [Standard Deviation and Variance](#standard-deviation-and-variance)
    - [Reshape and Transpose](#reshape-and-transpose)
    - [Dot Product vs Element Wise](#dot-product-vs-element-wise)
    - [Exercise: Nut Butter Store Sales](#exercise-nut-butter-store-sales)
    - [Comparison Operators](#comparison-operators)
    - [Sorting Arrays](#sorting-arrays)
    - [Turn Images Into NumPy Arrays](#turn-images-into-numpy-arrays)
    - [Optional: Extra NumPy resources](#optional-extra-numpy-resources)
  - [**Section 8: Matplotlib: Plotting and Data Visualization**](#section-8-matplotlib-plotting-and-data-visualization)
    - [Data Visualizations](#data-visualizations)
    - [Matplotlib Introduction](#matplotlib-introduction)
    - [Importing And Using Matplotlib](#importing-and-using-matplotlib)
    - [Anatomy Of A Matplotlib Figure](#anatomy-of-a-matplotlib-figure)
    - [Scatter Plot And Bar Plot](#scatter-plot-and-bar-plot)
    - [Histograms](#histograms)
    - [Subplots](#subplots)
    - [Plotting From Pandas DataFrames](#plotting-from-pandas-dataframes)
    - [Customizing Your Plots](#customizing-your-plots)
  - [**Section 9: Scikit-learn: Creating Machine Learning Models**](#section-9-scikit-learn-creating-machine-learning-models)
    - [Scikit-learn Introduction](#scikit-learn-introduction)
    - [Refresher: What Is Machine Learning?](#refresher-what-is-machine-learning)
  - [**Section 10: Supervised Learning: Classification + Regression**](#section-10-supervised-learning-classification--regression)
  - [**Section 11: Milestone Project 1: Supervised Learning (Classification)**](#section-11-milestone-project-1-supervised-learning-classification)
  - [**Section 12: Milestone Project 2: Supervised Learning (Time Series Data)**](#section-12-milestone-project-2-supervised-learning-time-series-data)
  - [**Section 13: Data Engineering**](#section-13-data-engineering)
  - [**Section 14: Neural Networks: Deep Learning, Transfer Learning and TensorFlow 2**](#section-14-neural-networks-deep-learning-transfer-learning-and-tensorflow-2)
  - [**Section 15: Storytelling + Communication: How To Present Your Work**](#section-15-storytelling--communication-how-to-present-your-work)
  - [**Section 16: Career Advice + Extra Bits**](#section-16-career-advice--extra-bits)
  - [**Section 17: Learn Python**](#section-17-learn-python)
  - [**Section 18: Learn Python Part 2**](#section-18-learn-python-part-2)
  - [**Section 19: Bonus: Learn Advanced Statistics and Mathematics for FREE!**](#section-19-bonus-learn-advanced-statistics-and-mathematics-for-free)
  - [**Section 20: Where To Go From Here?**](#section-20-where-to-go-from-here)
  - [**Section 21: Extras**](#section-21-extras)

## **Section 2: Machine Learning 101**

### What Is Machine Learning?

- Machines can perform tasks really fast
- We give them instructions to do tasks and they do it for us
- Computers used to mean people who do tasks that compute
- Problem: How to get to Danielle's house using Google maps?
- Imagine we had ten different routes to Danielle's house
  - Option 1: I measure each route one by one
  - Option 2: I program and tell the computer to calculate these 10 routes and find the shortest one.
- Problem: Somebody left a review on Amazon. Is this person angry?
- How can I describe to a computer what angry means?
- We let machines take care of the easier part of which things we can describe
- Things that are hard to just give instructions to, we let human do it
- The goal of machine learning is to make machines act more and more like humans because the smarter they

**[⬆ back to top](#table-of-contents)**

### [AI/Machine Learning/Data Science](https://towardsdatascience.com/a-beginners-guide-to-data-science-55edd0288973)

- AI: machine that acts like human
- Narrow AI: machine that acts like human at a specific task
- General AI: machine that acts like human with multiple abilities
- Machine Learning: a subset of AI
- Machine Learning: an approach to achieve artificial intelligence through systems that can find patterns in a set of data
- Machine Learning: the science of getting computers to act without being explicitly programmed
- Deep Learning: a subset of Machine Learning
- Deep Learning: one of the techniques for implementing machine learning
- Data Science: analyzing data and then doing something with a business goal
- [Teachable Machine](https://teachablemachine.withgoogle.com/)

**[⬆ back to top](#table-of-contents)**

### How Did We Get Here?

- Goal: Make business decisions
- Spreadsheets -> Relational DB -> Big Data (NoSQL) -> Machine Learning
  - Massive amounts of data
  - Massive improvements in computation
- Steps in a full machine learning project
  - Data collection (hardest part) -> Data modelling -> Deployment
- Data collection
  - How to clean noisy data?
  - What can we grab data from?
  - How do we find data?
  - How do we clean it so we can actually learn from it?
  - How to turn data from useless to useful?
- Data modelling
  - Problem definition: What problem are we trying to solve?
  - Data: What data do we have?
  - Evaluation: What defines success?
  - Features: What features should we model?
  - Modelling: What kind of model should we use?
  - Experiments: What have we tried / What else can we try?
- [Machine Learning Playground](https://ml-playground.com)

**[⬆ back to top](#table-of-contents)**

### [Types of Machine Learning](http://vas3k.com/blog/machine_learning/)

- Predict results based on incoming data
- Supervised: Data are labeled into categories
  - classification: is this an apple or is this a pear?
  - regression: based on input to predict stock prices
- Unsupervised: Data don't have labels
  - clustering: machine to create these groups
  - association rule learning: associate different things to predict what a customer might buy in the future
- Reinforcement: teach machines through trial and error
- Reinforcement: teach machines through rewards and punishment
  - skill acquisition
  - real time learning

**[⬆ back to top](#table-of-contents)**

### What Is Machine Learning? Round 2

- Now: Data -> machine learning algorithm -> pattern
- Future: New data -> Same algorithm (model) -> More patterns
- Normal algorithm: Starts with inputs and steps -> Makes output
- Machine learning algorithm
  - Starts with inputs and output -> Figures out the steps
- Data analysis is looking at a set of data and gain an understanding of it by comparing different examples, different features and making visualizations like graphs
- Data science is running experiments on a set of data with the hopes of finding actionable insights within it
  - One of these experiments is to build a machine learning model
- Data Science = Data analysis + Machine learning
- Section Review
  - Machine Learning lets computers make decisions about data
  - Machine Learning lets computers learn from data and they make predictions and decisions
  - Machine can learn from big data to predict future trends and make business decision

**[⬆ back to top](#table-of-contents)**

## **Section 3: Machine Learning and Data Science Framework**

### Introducing Our Framework

- Focus on practical solutions and writing machine learning code
- Steps to learn machine learning
  - Create a framework
  - Match to data science and machine learning tools
  - Learn by doing

**[⬆ back to top](#table-of-contents)**

### [6 Step Machine Learning Framework](https://www.mrdbourke.com/a-6-step-field-guide-for-building-machine-learning-projects/)

- Problem definition: What problems are we trying to solve?
  - Supervised or Unsupervised
  - Classification or Regression
- Data: What kind of data do we have?
  - Structured or Unstructured
- Evaluation: What defines success for us?
  - Example: House data -> Machine learning model -> House price
  - Predicted price vs Actual price
- Features: What do we already know about the data?
  - Example: Heart disease? Feature: body weight
  - Turn features such as weight into patterns to make predictions whether a patient has heart disease?
- Modelling: Based on our problem and data, what model should we use?
  - Problem 1 -> Model 1
  - Problem 2 -> Model 2
- Experimentation: How could we improve/what can we try next?

**[⬆ back to top](#table-of-contents)**

### Types of Machine Learning Problems

- When shouldn't you use machine learning?
  - When a simple hand-coded instruction based system will work
- Main types of machine learning
  - Supervised Learning
  - Unsupervised Learning
  - Transfer Learning
  - Reinforcement Learning
- Supervised Learning: data and label -> make prediction
  - Classification: Is this example one thing or another?
    - Binary classification = two options
    - Example: heart disease or no heart disease?
    - Multi-class classification = more than two options
  - Regression: Predict a number
    - Example: How much will this house sell for?
    - Example: How many people will buy this app?
- Unsupervised Learning: has data but no labels
  - Existing Data: Purchase history of all customers
  - Scenario: Marketing team want to send out promotion for next summer
  - Question: Do you know who is interested in summer clothes?
  - Process: Apply labels such as Summer or Winter to data
  - Solution: Cluster 1 (Summer) and Cluster 2 (Winter)
- Transfer Learning: leverages what one machine learning model has learned in another machine learning model
  - Example: Predict what dog breed appears in a photo
  - Solution: Find an existing model which is learned to decipher different car types and fine tune it for your task
- Reinforcement Learning: a computer program perform some actions within a defined space and rewarding it for doing it well or punishing it for doing poorly
  - Example: teach a machine learning algorithm to play chess
- Matching your problem
  - Supervised Learning: I know my inputs and outputs
  - Unsupervised Learning: I am not sure of the outputs but I have inputs
  - Transfer Learning: I think my problem may be similar to something else

**[⬆ back to top](#table-of-contents)**

### Types of Data: What kind of data do we have?

- Different types of data
  - Structured data: all of the samples have similar format
  - Unstructured data: images and natural language text such as phone calls, videos and audio files
  - Static: doesn't change over time, example: csv
    - More data -> Find patterns -> Predict something in the future
  - Streaming: data which is constantly changed over time
    - Example: predict how a stock price will change based on news headlines
    - News headlines are being updated constantly you'll want to see how they change stocks
- Start on static data and then if your data analysis and machine learning efforts prove to show some insights you'll move towards streaming data when you go to deployment or in production
- A data science workflow
  - open csv file in jupyter notebook (a tool to build machine learning project)
  - perform data analysis with panda (a python library for data analysis)
  - make visualizations such as graphs and comparing different data points with Matplotlib
  - build machine learning model on the data using scikit learn to predict using these patterns

**[⬆ back to top](#table-of-contents)**

### Types of Evaluation: What defines success for us?

- Example: if your problem is to use patient medical records to classify whether someone has heart disease or not you might start by saying for this project to be valuable we need a machine learning model with over 99% accuracy
- data -> machine learning model -> predict: heart disease? -> accurancy 97.8%
- predicting whether or not a patient has heart disease is an important task so you want a highly accurate model
- Different types of metrics for different problems
  - Classification: accurancy, percision, recall
  - Regression: Mean absolute error (MAE), Mean squared error (MSE), Root mean squared error (RMSE)
  - Recommendation: Precision at K
- Example: Classifying car insurance claims
  - text from car insurance claims -> machine learning model -> predict who caused the accident (person submitting the claim or the other person involved ?) -> min 95% accuracy who caused the accident (allow to get it wrong 1 out of 20 claims)

**[⬆ back to top](#table-of-contents)**

### Features In Data: What do we already know about the data?

- Features is another word for different forms of data
- Features refers to the different forms of data within structured or unstructured data
- For example: predict heart disease problem
  - Features of the data: weight, sex, heart rate
  - They can also be referred to as feature variables
  - We use the feature variables to predict the target variable which is whether a person has heart disease or no.
- Different features of data
  - numerical features: a number like body weight
  - categorical features: sex or whether a patient is a smoker or not
  - derived features: looks at different features of data and creates a new feature / alter existing feature
    - Example: look at someone's hospital visit history timestamps and if they've had a visit in the last year you could make a categorical feature called visited in last year. If someone had visited in the last year they would get true.
    - feature engineering: process of deriving features like this out of data
- Unstructured data has features too
  - a little less obvious if you looked at enough images of dogs you'd start to figure out
  - legs: most of these creatures have four shapes coming out of their body
  - eyes: a couple of circles up the front
  - machine learning algorithm figure out what features are there on its own
- What features should you use?
  - a machine learning algorithm learns best when all samples have similar information
  - feature coverage: process of ensuring all samples have similar information

**[⬆ back to top](#table-of-contents)**

### Modelling Part 1 - 3 sets

- Based on our problem and data, what model should we use?
- 3 parts to modelling
  - Choosing and training a model
  - Tuning a model
  - Model comparison
- The most important concept in machine learning (the training, validation and test sets or 3 sets)
  - Your data is split into 3 sets
    - training set: train your model on this
    - validation set: tune your model on this
    - test set: test and compare on this
  - at university
    - training set: study course materials
    - validation set: practice exam
    - test set: final exam
  - generalisation: the ability for a machine learning model to perform well on data it has not seen before
- When things go wrong
  - Your professor accidentally sent out the final exam for everyone to practice on
  - when it came time to the actual exam, everyone would have already seen it now
  - Since people know what they should be expecting they go through the exam
  - They answer all the questions with ease and everyone ends up getting top marks
  - Now top marks might appear good but did the students really learn anything or were they just expert memorization machines
  - for your machine learning models to be valuable at predicting something in the future on unseen data you'll want to avoid them becoming memorization machines
- split 100 patient records
  - training split: 70 patient records (70-80%)
  - validation split: 15 patient records (10-15%)
  - test split: 15 patient records (10-15%)

**[⬆ back to top](#table-of-contents)**

### Modelling Part 2 - Choosing

- Based on our problem and data, what model should we use?
- 3 parts to modelling
  - Choosing and training a model: training data
  - Tuning a model: validation data
  - Model comparison: test data
- Choosing a model
  - Problem 1 -> model 1
  - Problem 2 -> model 2
  - Structured Data: [CatBoost](https://catboost.ai/), [XGBoost](https://github.com/dmlc/xgboost), [Random Forest](https://towardsdatascience.com/understanding-random-forest-58381e0602d2)
  - Unstructured Data: Deep Learning, Transfer Learning
- Training a model
  - inputs: X(data) -> model -> predict outputs: y(label)
  - Goal: minimise time between experiments
    - Experiment 1: inputs -> model 1 -> outputs -> accurancy (87.5%) -> training time (3 min)
    - Experiment 2: inputs -> model 2 -> outputs -> accurancy (91.3%) -> training time (92 min)
    - Experiment 3: inputs -> model 3 -> outputs -> accurancy (94.7%) -> training time (176 min)
  - Things to remember
    - Some models work better than others and different problems
    - Don't be afraid to try things
    - Start small and build up (add complexity) as you need.

**[⬆ back to top](#table-of-contents)**

### Modelling Part 3 - Tuning

- Based on our problem and data, what model should we use?
- Example: Random Forest - adjust number of trees: 3, 5
- Example: Neural Networks - adjust number of layers: 2, 3
- Things to remember
  - Machine learning models have hyper parameters you can adjust
  - A model first results are not it's last
  - Tuning can take place on training or validation data sets

**[⬆ back to top](#table-of-contents)**

### Modelling Part 4 - Comparison

- How will our model perform in the real world?
- Testing a model
  - Data Set: Training -> Test
  - Performance: 98% -> 96%
- Underfitting (potential)
  - Data Set: Training -> Test
  - Performance: 64% -> 47%
- Overfitting (potential)
  - Data Set: Training -> Test
  - Performance: 93% -> 99%
- Balanced (Goldilocks zone)
- Data leakage -> Training Data overlap Test Data -> Overfitting
- Data mismatch -> Test Data is different to Training Data -> underfitting
- Fixes for underfitting
  - Try a more advanced model
  - Increase model hyperparameters
  - Reduce amount of features
  - Train longer
- Fixes for overfitting
  - Collect more data
  - Try a less advanced model
- Comparing models
  - Experiment 1: inputs -> model 1 -> outputs -> accurancy (87.5%) -> training time (3 min) -> prediction time (0.5 sec)
  - Experiment 2: inputs -> model 2 -> outputs -> accurancy (91.3%) -> training time (92 min) -> prediction time (1 sec)
  - Experiment 3: inputs -> model 3 -> outputs -> accurancy (94.7%) -> training time (176 min) -> prediction time (4 sec)
- Things to remember
  - Want to avoid overfitting and underfitting (head towards generality)
  - Keep the test set separate at all costs
  - Compare apples to apple
    - Model 1 on dataset 1
    - Model 2 on dataset 1
  - One best performance Metric does not equal the best model

**[⬆ back to top](#table-of-contents)**

### Experimentation

- How could we improve / what can we try next?
  - Start with a problem
  - Data Analysis: Data, Evaluation, Features
  - Machine learning modelling: Model 1
  - Experiments: Try model 2
- 6 Step Machine Learning Framework questions
  - Problem definition: What kind of problems you face day to day?
  - Data: What kind of data do you use?
  - Evaluation: What do you measure?
  - Features: What are features of your problems?
  - Modelling: What was the last thing you testing ability on?

**[⬆ back to top](#table-of-contents)**

### Tools We Will Use

- Data Science: 6 Step Machine Learning Framework
- Data Science: [Anaconda](https://www.anaconda.com/), [Jupyter Notebook](https://jupyter.org/)
- Data Analysis: Data, Evaluation and Features
- Data Analysis:[pandas](https://pandas.pydata.org/), [Matplotlib](https://matplotlib.org/), [NumPy](https://numpy.org/)
- Machine Learning: Modelling
- Machine Learning: [TensorFlow](https://www.tensorflow.org/), [PyTorch](https://pytorch.org/), [scikit-learn](https://scikit-learn.org/stable/), [XGBoost](https://xgboost.ai/), [CatBoost](https://catboost.ai/)
- [Elements of AI](https://www.elementsofai.com/)

**[⬆ back to top](#table-of-contents)**

## **Section 4: The 2 Paths**

- The 2 Paths
  - I know Python: Continue
  - I don't know Python: Goto Learn Python Section
- [Machine Learning Monthly and Web Developer Monthly](https://zerotomastery.io/blog/)

**[⬆ back to top](#table-of-contents)**

## **Section 5: Data Science Environment Setup**

### Introducing Our Tools

- Steps to learn machine learning [Recall]
  - Create a framework [Done] Refer to Section 3
  - Match to data science and machine learning tools
  - Learn by doing
- Your computer -> Setup Miniconda + Conda for Data Science
  - [Anaconda](https://www.anaconda.com/): Hardware Store = 3GB
  - [Miniconda](https://docs.conda.io/en/latest/miniconda.html): Workbench = 200 MB
  - [Anaconda vs. miniconda](https://stackoverflow.com/questions/45421163/anaconda-vs-miniconda)
  - [Conda](https://docs.conda.io/en/latest/): Personal Assistant
- Conda -> setup the rest of tools
  - Data Analysis:[pandas](https://pandas.pydata.org/), [Matplotlib](https://matplotlib.org/), [NumPy](https://numpy.org/)
  - Machine Learning: [TensorFlow](https://www.tensorflow.org/), [PyTorch](https://pytorch.org/), [scikit-learn](https://scikit-learn.org/stable/), [XGBoost](https://xgboost.ai/), [CatBoost](https://catboost.ai/)

**[⬆ back to top](#table-of-contents)**

### What is Conda?

- [Anaconda](https://www.anaconda.com/): Software Distributions
- [Miniconda](https://docs.conda.io/en/latest/miniconda.html): Software Distributions
- [Anaconda vs. miniconda](https://stackoverflow.com/questions/45421163/anaconda-vs-miniconda)
- [Conda](https://docs.conda.io/en/latest/): Package Manager
- Your computer -> Miniconda + Conda -> install other tools
  - Data Analysis:[pandas](https://pandas.pydata.org/), [Matplotlib](https://matplotlib.org/), [NumPy](https://numpy.org/)
  - Machine Learning: [TensorFlow](https://www.tensorflow.org/), [PyTorch](https://pytorch.org/), [scikit-learn](https://scikit-learn.org/stable/), [XGBoost](https://xgboost.ai/), [CatBoost](https://catboost.ai/)
- Conda -> Project 1: sample-project
- Resources
  - [Conda Cheatsheet](conda-cheatsheet.pdf)
  - [Getting started with conda](https://docs.conda.io/projects/conda/en/latest/user-guide/getting-started.html)
  - [Getting your computer ready for machine learning](https://www.mrdbourke.com/get-your-computer-ready-for-machine-learning-using-anaconda-miniconda-and-conda/)

**[⬆ back to top](#table-of-contents)**

### Conda Environments

- New Project: Heart disease?
- Your computer -> Project folder = Data + Conda Environment
- Your computer -> share Project folder -> Someone else's computer
- Someone else's computer -> Project folder = Data + Conda Environment

**[⬆ back to top](#table-of-contents)**

### Mac Environment Setup

- Resources
  - [Getting Started Anaconda, Miniconda and Conda](https://whimsical.com/BD751gt65nKjAD5i1CNEXU)
  - [Miniconda installers](https://docs.conda.io/en/latest/miniconda.html) - Choose latest pkg version
- Create conda environment: goto [sample-project](https://github.com/chesterheng/machine-learning-data-science/tree/master/sample-project) folder
  - `conda create --prefix ./env pandas numpy matplotlib scikit-learn`
- Activate conda environment: `conda activate /Users/xxx/Desktop/sample-project/env`
- List Conda environments: `conda env list`
  - `cd ~/.conda` -> `environments.txt`
- Deactivate conda environment: `conda deactivate`

**[⬆ back to top](#table-of-contents)**

### Mac Environment Setup 2

- Install Jupyter: `conda install jupyter`
- Run Jupyter Notebook: `jupyter notebook`
- Remove packages: `conda remove openpyxl xlrd`
- List all packages: `conda list`
- [sample-project](https://github.com/chesterheng/machinelearning-datascience/tree/master/sample-project)

**[⬆ back to top](#table-of-contents)**

### Sharing your Conda Environment

- Share a .yml file of your Conda environment: `conda env export --prefix ./env > environment.yml`
  - [Sharing an environment](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#sharing-an-environment)
- Create an environment called env_from_file from a .yml file: `conda env create --file environment.yml --name env_from_file`
  - [Creating an environment from an environment.yml file](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file)

**[⬆ back to top](#table-of-contents)**

### [Jupyter Notebook Walkthrough](https://github.com/chesterheng/machinelearning-datascience/blob/master/sample-project/example-notebook.ipynb)

- Project Folder
- Data -> Environment
- Data -> Jupyter Notebook (Workspace) -> matplotlib, numpy, pandas -> scikit-learn

**[⬆ back to top](#table-of-contents)**

## **Section 6: Pandas: Data Analysis**

### Pandas Introduction

- Why pandas?
  - Simple to use
  - Integrated with many other data science & ML Python Tools
  - Helps you get your data ready for machine learning
- [What are we going to cover?](https://pandas.pydata.org/pandas-docs/stable/getting_started/10min.html)
  - Most useful functions
  - pandas Datatypes
  - Importing & exporting data
  - Describing data
  - Viewing & Selecting data
  - Manipulating data
- Where can you get help?
  - Follow along with the code
  - Try it for yourself
  - Search for it - stackoverflow, [pandas documentation](https://pandas.pydata.org/pandas-docs/stable/)
  - Try again
  - Ask
- Let's code

**[⬆ back to top](#table-of-contents)**

### [Series, Data Frames and CSVs](https://github.com/chesterheng/machinelearning-datascience/blob/master/sample-project/introduction-to-pandas.ipynb)

- 2 main datatypes

```python
  # 1-dimenional data (Column)
  series = pd.Series(["BMW", "Toyota", "Honda"])
  colours = pd.Series(["Red", "Blue", "White"])
  # DataFrame: 2-dimenional data (Table)
  car_data = pd.DataFrame({ "Car make": series, "Colour": colours })
```

- Import data and export to csv

```python
  car_sales = pd.read_csv("car-sales.csv")
  car_sales.to_csv("exported-car-sales.csv", index=False)
  export_car_sales = pd.read_csv("exported-car-sales.csv")
```

- Import data and export to excel

```python
  car_sales = pd.read_csv("car-sales.csv")
  car_sales.to_excel("exported-car-sales.xlsx", index=False)
  export_car_sales = pd.read_excel("exported-car-sales.xlsx")
```

- `conda install openpyxl xlrd` cannot work -> ModuleNotFoundError
- `pip3 install openpyxl xlrd` work

**[⬆ back to top](#table-of-contents)**

### Data from URLs

```python
heart_disease = pd.read_csv("data/heart-disease.csv")
heart_disease = pd.read_csv("https://raw.githubusercontent.com/mrdbourke/zero-to-mastery-ml/master/data/heart-disease.csv")
```

**[⬆ back to top](#table-of-contents)**

### [Describing Data with Pandas](https://github.com/chesterheng/machinelearning-datascience/blob/master/sample-project/introduction-to-pandas.ipynb)

```python
# Attribute - information
car_sales.dtypes

# Function - contain code to execute
# car_sales.to_csv()

car_sales_columns = car_sales.columns # get all columns
car_sales_index = car_sales.index # get index column
car_sales.describe() # get count, mean, std, min, max, percentile
car_sales.info() # get details of car_sales
car_sales.mean()
car_prices = pd.Series([3000, 1500, 111250])
car_prices.mean()
car_sales.sum()
car_sales["Doors"].sum()
len(car_sales)
```

**[⬆ back to top](#table-of-contents)**

### [Selecting and Viewing Data with Pandas](https://github.com/chesterheng/machinelearning-datascience/blob/master/sample-project/introduction-to-pandas.ipynb)

```python
car_sales.head() # get top 5 rows of car_sales
car_sales.head(7) # get top 7 rows of car_sales
car_sales.tail() # get bottom 5 rows of car_sales

# index [0, 3, 9, 8, 3] => ["cat", "dog", "bird", "panda", "snake"]
animals = pd.Series(["cat", "dog", "bird", "panda", "snake"], index=[0, 3, 9, 8, 3])
animals.loc[3]  # loc refers to index
animals.iloc[3] # iloc refers to position
car_sales.loc[3]  # car_sales item has same position and index
car_sales.iloc[3]

animals.iloc[:3]  # 1st to 3rd positions, 4th is excluded
car_sales.loc[:3] # index 0 to 3 (included)

car_sales["Make"] # get column Make method 1 - column name can be more than 2 words with space
car_sales.Make  # get column Make method 2 - column name must be 1 word without space

car_sales[car_sales["Make"] == "Toyota"] # select rows with criteria - ["Make"] == "Toyota"
car_sales[car_sales["Odometer (KM)"] > 100000] # select rows with criteria - ["Odometer (KM)"] > 100000
pd.crosstab(car_sales["Make"], car_sales["Doors"]) # show the relationshop of "Make" and "Doors"
car_sales.groupby(["Make", "Colour"]).mean() # group row by "Make", then "Colour"

car_sales["Odometer (KM)"].plot() # plot a line graph
car_sales["Odometer (KM)"].hist() # plot a histogram
car_sales["Price"].dtype # check data type of "Price" column
# convert "Price" column value to integer type
car_sales["Price"] = car_sales["Price"].str.replace('[\$\,\.]','').astype(int)
```

**[⬆ back to top](#table-of-contents)**

### [Manipulating Data](https://github.com/chesterheng/machinelearning-datascience/blob/master/sample-project/introduction-to-pandas.ipynb)

- [Data Manipulation with Pandas](https://jakevdp.github.io/PythonDataScienceHandbook/03.00-introduction-to-pandas.html)

```python
car_sales["Make"].str.lower()
car_sales["Make"] = car_sales["Make"].str.lower()

car_sales_missing = pd.read_csv("car-sales-missing-data.csv")
odometer-mean = car_sales_missing["Odometer"].mean() # get the mean value of Odometer column

car_sales_missing["Odometer"].fillna(odometer-mean) #   replace NaN with mean value
# update car_sales_missing method 1 - inplace=True
car_sales_missing["Odometer"].fillna(odometer-mean, inplace=True)
# update car_sales_missing method 2 - assign new values to car_sales_missing["Odometer"]
car_sales_missing["Odometer"] = car_sales_missing["Odometer"].fillna(car_sales_missing["Odometer"].mean())

car_sales_missing.dropna(inplace=True)
car_sales_missing_dropped = car_sales_missing.dropna()
car_sales_missing_dropped.to_csv("car-sales-missing-dropped.csv")

# Create a column from series
seats_column = pd.Series([5, 5, 5, 5, 5])
car_sales["Seats"] = seats_column
car_sales["Seats"].fillna(5, inplace=True)

# Create a column from Python list
# list must have same length as exsiting data frame
fuel_economy = [7.5, 9.2, 5.0, 9.6, 8.7, 4.7, 7.6, 8.7, 3.0, 4.5]
car_sales["Fuel per 100KM"] = fuel_economy

# Derived a column
car_sales["Total fuel used (L)"] = car_sales["Odometer (KM)"] / 100 * car_sales["Fuel per 100KM"]
car_sales["Total fuel used"] = car_sales["Odometer (KM)"] / 100 * car_sales["Fuel per 100KM"]

# Create a column from a single value
car_sales["Number of wheels"] = 4
car_sales["Passed road safety"] = True

# Delete a column
# axis=1 - refer to column
car_sales.drop("Total fuel used", axis=1, inplace=True)

# get a sample data set - 20% of data
car_sales_shuffled = car_sales.sample(frac=0.2)

# reset index column to original value
car_sales_shuffled.reset_index(drop=True, inplace=True)

# apply lambda function to Odometer (KM) column
car_sales["Odometer (KM)"] = car_sales["Odometer (KM)"].apply(lambda x: x / 1.6)
```

**[⬆ back to top](#table-of-contents)**

### Assignment: Pandas Practice

- [pandas documentation](https://pandas.pydata.org/pandas-docs/stable/)
- [10 minutes to pandas](https://pandas.pydata.org/pandas-docs/stable/getting_started/10min.html)
- [top questions and answers on Stack Overflow for pandas](https://stackoverflow.com/questions/tagged/pandas?sort=MostVotes&edited=true)
- [Google Colab](https://colab.research.google.com)

**[⬆ back to top](#table-of-contents)**

## **Section 7: NumPy**

### Section Overview

- Why NumPy?
  - performance advantage as it is written in C under the hood
  - convert data into 1 or 0 so machine can understand
- [What is the difference between NumPy and Pandas?](https://www.quora.com/What-is-the-difference-between-NumPy-and-Pandas)

**[⬆ back to top](#table-of-contents)**

### NumPy Introduction

- Machine learning start with data.
  - Example: data frame
  - Numpy turn data into a series of numbers
  - A machine learning algorithm work out the patterns in those numbers
- Why NumPy?
  - It's fast
  - Behind the scenes optimizations written in C
  - [Vectorization via broadcasting (avoiding loops)](https://simpleprogrammer.com/vectorization-and-broadcasting/)
    - vector is a 1D array
    - matrix is a 2D array
    - vectorization: perform math operations on 2 vectors
    - broadcasting: extend an array to a shape that will allow it to successfully take part in a vectorized calculation
  - Backbone of other Python scientific packages
- What are we going to to cover?
  - Most useful functaions
  - NumPy datatypes & attributes (ndarray)
  - Creating arrays
  - Viewing arrays & matrices
  - Manipulating & comparing arrays
  - Sorting arrays
  - Use cases
- Where can you get help?
  - Follow along with the code
  - Try it for yourself
  - Search for it - stackoverflow, [NumPy Documentation](https://numpy.org/doc/)
  - Try again
  - Ask
- Let's code

**[⬆ back to top](#table-of-contents)**

### [NumPy DataTypes and Attributes](https://github.com/chesterheng/machinelearning-datascience/blob/master/sample-project/introduction-to-numpy.ipynb)

```python
import numpy as np

a1 = np.array([1, 2, 3])
a2 = np.array([[1, 2, 3.3],
               [4, 5, 6.5]])
a3 = np.array([[[1, 2, 3],
                [4, 5, 6],
                [7, 8, 9]],
                [[10, 11, 12],
                 [13, 14, 15],
                 [16, 17, 18]]])
a1.shape, a2.shape, a3.shape
a1.ndim, a2.ndim, a3.ndim
a1.dtype, a2.dtype, a3.dtype
a1.size, a2.size, a3.size
type(a1), type(a2), type(a3)

import pandas as pd
df = pd.DataFrame(a2)
```

**[⬆ back to top](#table-of-contents)**

### [Creating NumPy Arrays](https://github.com/chesterheng/machinelearning-datascience/blob/master/sample-project/introduction-to-numpy.ipynb)

```python
import numpy as np

sample_array = np.array([1, 2, 3])
ones = np.ones((2, 3))
zeros = np.zeros((2, 3))
range_array = np.arange(0, 10, 2) # array([0, 2, 4, 6, 8])
random_array = np.random.randint(0, 10, size=(3, 5))
random_array_2 = np.random.random((5, 3))
random_array_3 = np.random.rand(5, 3)
```

**[⬆ back to top](#table-of-contents)**

### [NumPy Random Seed](https://github.com/chesterheng/machinelearning-datascience/blob/master/sample-project/introduction-to-numpy.ipynb)

```python
import numpy as np

np.random.seed(seed=0) # define a seed for random number
random_array_4 = np.random.randint(10, size=(5, 3))

np.random.seed(7)
random_array_5 = np.random.random((5, 3))
```

**[⬆ back to top](#table-of-contents)**

### [Viewing Arrays and Matrices](https://github.com/chesterheng/machinelearning-datascience/blob/master/sample-project/introduction-to-numpy.ipynb)

```python
import numpy as np

np.unique(random_array_4)

a3[:2, :2, :2]

a4 = np.random.randint(10, size=(2, 3, 4, 5))
a4[:, :, :, :4] # Get the first 4 numbers of the inner most arrays
```

**[⬆ back to top](#table-of-contents)**

### [Manipulating Arrays](https://github.com/chesterheng/machinelearning-datascience/blob/master/sample-project/introduction-to-numpy.ipynb)

```python
import numpy as np

# Arithmetic
ones = np.ones(3)
a1 + ones
a1 - ones
a1 * ones
a1 / ones
a2 // a1  # Floor division removes the decimals (rounds down)
a2 ** 2
np.square(a2)
np.add(a1, ones)
a1 % 2
np.exp(a1)
np.log(a1)

# Aggregation
massive_array = np.random.random(100000)
%timeit sum(massive_array) # Measure Python's sum () execution time
%timeit np.sum(massive_array) # Measure NumPy's sum () execution time

np.mean(a2)
np.max(a2)
np.min(a2)
```

**[⬆ back to top](#table-of-contents)**

### [Standard Deviation and Variance](https://github.com/chesterheng/machinelearning-datascience/blob/master/sample-project/introduction-to-numpy.ipynb)

- [Standard Deviation and Variance](https://www.mathsisfun.com/data/standard-deviation.html)
- [Outlier Detection Methods](https://docs.oracle.com/cd/E17236_01/epm.1112/cb_statistical/frameset.htm?ch07s02s10s01.html)
  - If a value is a certain number of standard deviations away from the mean, that data point is identified as an outlier. 
  - The specified number of standard deviations is called the threshold. The default value is 3.

```python
import numpy as np

# Standard deviation
# a measure of how spread out a group of numbers is from the mean
np.std(a2)

# measure of the average degree to which each number is different
# Higher variance = wider range of numbers
# Lower variance = lower range of numbers
np.var(a2)
np.sqrt(np.var(a2)) # Standard deviation = squareroot of variance

high_var_array = np.array([1, 100, 200, 300, 4000, 5000])
low_var_array = np.array([2, 4, 6, 8, 10])
np.var(high_var_array), np.var(low_var_array)
np.std(high_var_array), np.std(low_var_array)
np.mean(high_var_array), np.mean(low_var_array)

%matplotlib inline
import matplotlib.pyplot as plt
plt.hist(high_var_array)
plt.show()

plt.hist(low_var_array)
plt.show()
```

**[⬆ back to top](#table-of-contents)**

### [Reshape and Transpose](https://github.com/chesterheng/machinelearning-datascience/blob/master/sample-project/introduction-to-numpy.ipynb)

```python
import numpy as np

a2_reshape = a2.reshape((2, 3, 1))
a2_reshape * a3

a2.T  # Transpose - switches the axis
a3.T.shape

```

**[⬆ back to top](#table-of-contents)**

### [Dot Product vs Element Wise](https://github.com/chesterheng/machinelearning-datascience/blob/master/sample-project/introduction-to-numpy.ipynb)

- [Matrix Multiplication](http://matrixmultiplication.xyz/)

```python
import numpy as np

np.random.seed(0)
mat1 = np.random.randint(10, size=(5, 3))
mat2 = np.random.randint(10, size=(5, 3))
mat1.shape, mat2.shape

# Element-wise multiplication, also known as Hadamard product
mat1 * mat2

mat1.shape, mat2.T.shape
mat3 = np.dot(mat1, mat2.T)

```

**[⬆ back to top](#table-of-contents)**

### [Exercise: Nut Butter Store Sales](https://github.com/chesterheng/machinelearning-datascience/blob/master/sample-project/introduction-to-numpy.ipynb)

```python
np.random.seed(0)
# Number of jars sold
sales_amounts = np.random.randint(20, size=(5,3))
# Create weekly_sales DataFrame
weekly_sales = pd.DataFrame(sales_amounts,
                            index=["Mon", "Tues", "Wed", "Thurs", "Fri"],
                            columns=["Almond butter", "Peanut butter", "Cashew butter"])

# Create prices array
prices = np.array([10, 8, 12])
# Create butter_prices DataFrame
butter_prices = pd.DataFrame(prices.reshape(1, 3),
                             index=["Price"],
                             columns=["Almond butter", "Peanut butter", "Cashew butter"])

total_sales = prices.dot(sales_amounts.T)
daily_sales = butter_prices.dot(weekly_sales.T)
weekly_sales["Total ($)"] = daily_sales.T
```

**[⬆ back to top](#table-of-contents)**

### [Comparison Operators](https://github.com/chesterheng/machinelearning-datascience/blob/master/sample-project/introduction-to-numpy.ipynb)

```python
a1 > a2
bool_array = a1 >= a2
type(bool_array), bool_array.dtype

a1 > 5
a1 < 5
a1 == a1
a1 == a2
```

**[⬆ back to top](#table-of-contents)**

### [Sorting Arrays](https://github.com/chesterheng/machinelearning-datascience/blob/master/sample-project/introduction-to-numpy.ipynb)

```python
random_array = np.random.randint(10, size=(3, 5))
np.sort(random_array)
np.argsort(random_array) # sort and shiw show index

np.argmin(a1)
np.argmax(a1)

np.argmax(random_array, axis=0) # compare elements in a column
np.argmax(random_array, axis=1) # compare elements in a row
```

**[⬆ back to top](#table-of-contents)**

### [Turn Images Into NumPy Arrays](https://github.com/chesterheng/machinelearning-datascience/blob/master/sample-project/introduction-to-numpy.ipynb)

```python
from matplotlib.image import imread
panda = imread("numpy-panda.png")
panda.size, panda.shape, panda.ndim
panda[:5]
```

**[⬆ back to top](#table-of-contents)**

### Optional: Extra NumPy resources

- [The Basics of NumPy Arrays](https://jakevdp.github.io/PythonDataScienceHandbook/02.02-the-basics-of-numpy-arrays.html)
- [A Visual Intro to NumPy and Data Representation](http://jalammar.github.io/visual-numpy/)
- [NumPy Quickstart tutorial](https://numpy.org/doc/1.17/user/quickstart.html)

**[⬆ back to top](#table-of-contents)**

## **Section 8: Matplotlib: Plotting and Data Visualization**

### Data Visualizations

- [5 Essential Tips for Creative Storytelling Through Data Visualization](https://boostlabs.com/storytelling-through-data-visualization/)
- [Storytelling with Data: A Data Visualization Guide for Business Professionals](https://towardsdatascience.com/storytelling-with-data-a-data-visualization-guide-for-business-professionals-97d50512b407)

**[⬆ back to top](#table-of-contents)**

### [Matplotlib](https://matplotlib.org/3.1.1/contents.html) Introduction

- What is Matplotlib
  - Python ploting library
  - Turn date into visualisation
- Why Matplotlib?
  - BUilt on NumPy arrays (and Python)
  - Integrates directly with pandas
  - Can create basic or advanced plots
  - Simple to use interface (once you get the foundations)
- What are we going to cover?
  - A Matplotlib workflow
    - Create data
    - Create plot (figure)
    - Plot data (axes on figure)
    - Customise plot
    - Save/share plot
  - Importing Matplotlib and the 2 ways of plotting Plotting data - from NumPy arrays
  - Plotting data from pandas DataFrames Customizing plots
  - Saving and sharing plots

```python
# Potential function
def plotting_workflow(data):

  # 1. Manipulate data

  # 2. Create plot

  # 3. Plot data

  # 4. Customize plot

  # 5. Save plot

  # 6. Return plot
  return plot
```

**[⬆ back to top](#table-of-contents)**

### [Importing And Using Matplotlib](https://github.com/chesterheng/machinelearning-datascience/blob/master/sample-project/introduction-to-matplotlib.ipynb)

- Which one should you use? (pyplpt vs matplotlib OO method?)
  - When plotting something quickly, okay to use pyplot method
  - When plotting something more customized and advanced, use the OO method
- [Effectively Using Matplotlib](https://pbpython.com/effective-matplotlib.html)
- [Pyplot tutorial](https://matplotlib.org/3.2.1/tutorials/introductory/pyplot.html)
- [The Lifecycle of a Plot](https://matplotlib.org/3.2.1/tutorials/introductory/lifecycle.html)

```python
%matplotlib inline
import matplotlib.pyplot as plt
import pandas as pd
import numpy as np

# Pyplot interface
# based on MATLAB and uses a state-based interface
plt.plot()
plt.plot(); #add ; to remove []
plt.plot()
plt.show()
plt.plot([1, 2, 3, 4]) # assume x = [0, 1, 2, 3]
x = [1, 2, 3, 4]
y = [11, 22, 33, 44]
plt.plot(x, y)

# Object-Oriented (OO) interface
# utilize an instance of axes.Axes in order to 
# render visualizations on an instance of figure.Figure

# 1st method
fig = plt.figure() # creates a figure
ax = fig.add_subplot() # adds some axes
plt.show()

# 2nd method
fig = plt.figure() # creates a figure
ax = fig.add_axes([1, 1, 1, 1])
ax.plot(x, y) # add some data
plt.show()

# 3rd method (recommended)
fig, ax = plt.subplots()
ax.plot(x, y); # add some data
```

**[⬆ back to top](#table-of-contents)**

### [Anatomy Of A Matplotlib Figure](https://github.com/chesterheng/machinelearning-datascience/blob/master/sample-project/introduction-to-matplotlib.ipynb)

- [Anatomy of a figure](https://matplotlib.org/examples/showcase/anatomy.html)

```python
# 0. import matplotlib and get it ready for plotting in Jupyter
%matplotlib inline
import matplotlib.pyplot as plt

# 1. Prepare data
x = [1, 2, 3, 4]
y = [11, 22, 33, 44]

# 2. Setup plot
fig, ax = plt.subplots(figsize=(10,10)) # figsize dimension is inches

# 3. Plot data
ax.plot(x, y)

# 4. Customize plot
ax.set(title="Sample Simple Plot", xlabel="x-axis", ylabel="y-axis")

# 5. Save & show
fig.savefig("images/simple-plot.png")
```

**[⬆ back to top](#table-of-contents)**

### [Scatter Plot And Bar Plot](https://github.com/chesterheng/machinelearning-datascience/blob/master/sample-project/introduction-to-matplotlib.ipynb)

- [A quick review of Numpy and Matplotlib](https://towardsdatascience.com/a-quick-review-of-numpy-and-matplotlib-48f455db383)

```python
import numpy as np
x = np.linspace(0, 10, 100)

# Plot the data and create a line plot
fig, ax = plt.subplots()
ax.plot(x, x**2);

# Use same data to make a scatter
fig, ax = plt.subplots()
ax.scatter(x, np.exp(x));

# Make a Bar plot from dictionary
nut_butter_prices = {"Almond butter": 10,
                     "Peanut butter": 8,
                     "Cashew butter": 12}
fig, ax = plt.subplots()
ax.bar(nut_butter_prices.keys(), nut_butter_prices.values())
ax.set(title="Dan's Nut Butter Store", ylabel="Price ($)");

# Make a horizontal bar plot
fig, ax = plt.subplots()
ax.barh(list(nut_butter_prices.keys()), list(nut_butter_prices.values()));
```

**[⬆ back to top](#table-of-contents)**

### [Histograms](https://github.com/chesterheng/machinelearning-datascience/blob/master/sample-project/introduction-to-matplotlib.ipynb)

```python
# Make a Histogram plot
x = np.random.randn(1000) # Make some data from a normal distribution
fig, ax = plt.subplots()
ax.hist(x);

x = np.random.random(1000) # random data from random distribution
fig, ax = plt.subplots()
ax.hist(x);
```

**[⬆ back to top](#table-of-contents)**

### [Subplots](https://github.com/chesterheng/machinelearning-datascience/blob/master/sample-project/introduction-to-matplotlib.ipynb)

```python
# Subplots Option 1: Create multiple subplots
fig, ((ax1, ax2), (ax3, ax4)) = plt.subplots(nrows=2, 
                                             ncols=2, 
                                             figsize=(10, 5))
# Plot data to each different axis
ax1.plot(x, x/2);
ax2.scatter(np.random.random(10), np.random.random(10));
ax3.bar(nut_butter_prices.keys(), nut_butter_prices.values());
ax4.hist(np.random.randn(1000));

# Subplots Option 2: Create multiple subplots
fig, ax = plt.subplots(nrows=2, ncols=2, figsize=(10, 5))
# Plot to each different index
ax[0, 0].plot(x, x/2);
ax[0, 1].scatter(np.random.random(10), np.random.random(10));
ax[1, 0].bar(nut_butter_prices.keys(), nut_butter_prices.values());
ax[1, 1].hist(np.random.randn(1000));
```

**[⬆ back to top](#table-of-contents)**

### [Plotting From Pandas DataFrames](https://github.com/chesterheng/machinelearning-datascience/blob/master/sample-project/introduction-to-matplotlib.ipynb)

- Which one should you use? (pyplpt vs matplotlib OO method?)
  - When plotting something quickly, okay to use pyplot method
  - When plotting something more advanced, use the OO method
- [Regular Expressions](https://regexone.com/)
- [Visualization](https://pandas.pydata.org/pandas-docs/stable/user_guide/visualization.html)

```python
import pandas as pd

ts = pd.Series(np.random.randn(1000),
               index=pd.date_range('1/1/2020', periods=1000))
ts = ts.cumsum() # Return cumulative sum over a DataFrame or Series
ts.plot();

# Make a dataframe
car_sales = pd.read_csv("data/car-sales.csv")

# Remove price column symbols
car_sales["Price"] = car_sales["Price"].str.replace('[\$\,\.]', '')
type(car_sales["Price"][0])
# Remove last two zeros from price
#  4    0   0   0   0   0
# [-6][-5][-4][-3][-2][-1]
car_sales["Price"] = car_sales["Price"].str[:-2]

car_sales["Sale Date"] = pd.date_range("1/1/2020", periods=len(car_sales))
type(car_sales["Price"][0])

car_sales["Total Sales"] = car_sales["Price"].astype(int).cumsum()

car_sales.plot(x="Sale Date", y="Total Sales");
car_sales["Price"] = car_sales["Price"].astype(int) # Reassign price column to int

# Plot scatter plot with price column as numeric 
car_sales.plot(x="Odometer (KM)", y="Price", kind="scatter");

# How aboute a bar graph?
x = np.random.rand(10, 4)
df = pd.DataFrame(x, columns=['a', 'b', 'c', 'd'])
df.plot.bar();
df.plot(kind='bar');  # Can do the same thing with 'kind' keyword

car_sales.plot(x='Make', y='Odometer (KM)', kind='bar');

# How about Histograms?
car_sales["Odometer (KM)"].plot.hist();
# bins=10 default , bin width = 25,car_sales["Price"].plot.hist(bins=10);000
car_sales["Odometer (KM)"].plot(kind="hist");
# Default number of bins is 10, bin width = 12,500
car_sales["Odometer (KM)"].plot.hist(bins=20);

# Let's try with another dataset
heart_disease = pd.read_csv("data/heart-disease.csv")
# Create a histogram of age
heart_disease["age"].plot.hist(bins=50);
heart_disease.plot.hist(figsize=(10, 30), subplots=True);

over_50 = heart_disease[heart_disease["age"] > 50]
# Pyplot method
# c: change colur of plot base on target value [0, 1]
over_50.plot(kind='scatter', 
             x='age', 
             y='chol', 
             c='target', 
             figsize=(10, 6));

# OO method
fig, ax = plt.subplots(figsize=(10, 6))
over_50.plot(kind='scatter', 
             x="age", 
             y="chol", 
             c='target', 
             ax=ax);
ax.set_xlim([45, 100]);
over_50.target.values
over_50.target.unique()

# Make a bit more of a complicated plot

# Create the plot
fig, ax = plt.subplots(figsize=(10, 6))

# Plot the data
scatter = ax.scatter(over_50["age"], 
                     over_50["chol"], 
                     c=over_50["target"])

# Customize the plot
ax.set(title="Heart Disease and Cholesterol Levels",
       xlabel="Age",
       ylabel="Cholesterol");

# Add a legend
ax.legend(*scatter.legend_elements(), title="Target");

# Add a horizontal line
ax.axhline(over_50["chol"].mean(), linestyle="--");

# Setup plot (2 rows, 1 column)
fig, (ax0, ax1) = plt.subplots(nrows=2, # 2 rows
                               ncols=1, 
                               sharex=True, 
                               figsize=(10, 8))

# Add data for ax0
scatter = ax0.scatter(x=over_50["age"], 
                      y=over_50["chol"], 
                      c=over_50["target"])
# Customize ax0
ax0.set(title="Heart Disease and Cholesterol Levels",
#         xlabel="Age",
        ylabel="Cholesterol")
ax0.legend(*scatter.legend_elements(), title="Target")

# Setup a mean line
ax0.axhline(y=over_50["chol"].mean(), 
            color='b', 
            linestyle='--', 
            label="Average")

# Add data for ax1
scatter = ax1.scatter(over_50["age"], 
                      over_50["thalach"], 
                      c=over_50["target"])

# Customize ax1
ax1.set(title="Heart Disease and Max Heart Rate Levels",
        xlabel="Age",
        ylabel="Max Heart Rate")
ax1.legend(*scatter.legend_elements(), title="Target")

# Setup a mean line
ax1.axhline(y=over_50["thalach"].mean(), 
            color='b', 
            linestyle='--', 
            label="Average")

# Title the figure
fig.suptitle('Heart Disease Analysis', fontsize=16, fontweight='bold');
```

**[⬆ back to top](#table-of-contents)**

### [Customizing Your Plots](https://github.com/chesterheng/machinelearning-datascience/blob/master/sample-project/introduction-to-matplotlib.ipynb)

[Choosing Colormaps in Matplotlib](https://matplotlib.org/3.1.1/tutorials/colors/colormaps.html#sphx-glr-tutorials-colors-colormaps-py)

```python
plt.style.available
plt.style.use('seaborn-whitegrid')

# Create the plot
fig, ax = plt.subplots(figsize=(10, 6))

# Plot the data
scatter = ax.scatter(over_50["age"], 
                     over_50["chol"], 
                     c=over_50["target"],
                     cmap="winter") # this changes the color scheme

# Customize the plot
ax.set(title="Heart Disease and Cholesterol Levels",
       xlabel="Age",
       ylabel="Cholesterol");

# Add a legend
ax.legend(*scatter.legend_elements(), title="Target");

# Add a horizontal line
ax.axhline(over_50["chol"].mean(), linestyle="--");
```

```python
# Customizing the y and x axis limitations

# Setup plot (2 rows, 1 column)
fig, (ax0, ax1) = plt.subplots(nrows=2, # 2 rows
                               ncols=1, 
                               sharex=True, 
                               figsize=(10, 8))

# Add data for ax0
scatter = ax0.scatter(x=over_50["age"], 
                      y=over_50["chol"], 
                      c=over_50["target"],
                      cmap="winter") # this changes the color scheme
# Customize ax0
ax0.set(title="Heart Disease and Cholesterol Levels",
#         xlabel="Age",
        ylabel="Cholesterol")
ax0.set_xlim([50, 80])  # change the x axis limit
ax0.legend(*scatter.legend_elements(), title="Target")

# Setup a mean line
ax0.axhline(y=over_50["chol"].mean(), 
            color='r', 
            linestyle='--', 
            label="Average")

# Add data for ax1
scatter = ax1.scatter(over_50["age"], 
                      over_50["thalach"], 
                      c=over_50["target"],
                      cmap="winter") # this changes the color scheme

# Customize ax1
ax1.set(title="Heart Disease and Max Heart Rate Levels",
        xlabel="Age",
        ylabel="Max Heart Rate")
ax1.set_xlim([50, 80])  # change the x axis limit
ax1.set_ylim([60, 200]) # change the y axis limit
ax1.legend(*scatter.legend_elements(), title="Target")

# Setup a mean line
ax1.axhline(y=over_50["thalach"].mean(), 
            color='r', 
            linestyle='--', 
            label="Average")

# Title the figure
fig.suptitle('Heart Disease Analysis', fontsize=16, fontweight='bold');
```

**[⬆ back to top](#table-of-contents)**

## **Section 9: Scikit-learn: Creating Machine Learning Models**

### [Scikit-learn](https://scikit-learn.org/stable/user_guide.html) Introduction

- What is Scikit-Learn (sklearn)?
  - Scikit-Learn is a python machine learning library
  - Data -> Scikit-Learn -> machine learning model
  - machine learning model learn patterns in the data
  - machine learning model make prediction
- Why Scikit-Learn?
  - Built on NumPy and Matplotlib (and Python)
  - Has many in-built machine learning models
  - Methods to evaluate your machine learning models
  - Very well-designed API
- [What are we going to cover?](https://github.com/mrdbourke/zero-to-mastery-ml/blob/master/section-2-data-science-and-ml-tools/scikit-learn-what-were-covering.ipynb) An end-to-end Scikit-Learn workflow
  - Get data ready (to be used with machine learning models) 
  - [Pick a machine learning model](https://scikit-learn.org/stable/tutorial/machine_learning_map/index.html) (to suit your problem)
  - Fit a model to the data (learning patterns)
  - Make predictions with a model (using patterns)
  - [Evaluate the model](https://scikit-learn.org/stable/modules/model_evaluation.html)
  - Improving model predictions through experimentation
  - Saving and loading models
- Where can you get help?
  - Follow along with the code
  - Try it for yourself
  - Press SHIFT + TAB to read the docstring
  - Search for it
  - Try again
  - Ask

**[⬆ back to top](#table-of-contents)**

### Refresher: What Is Machine Learning?

- Programming: input -> function -> output
- Machine Learning: input (data) and desired output
  - machine figure out the function
  - a computer writing his own function
  - also know as model, alogrithm, bot
  - machine is the brain

**[⬆ back to top](#table-of-contents)**

## **Section 10: Supervised Learning: Classification + Regression**

**[⬆ back to top](#table-of-contents)**

## **Section 11: Milestone Project 1: Supervised Learning (Classification)**

**[⬆ back to top](#table-of-contents)**

## **Section 12: Milestone Project 2: Supervised Learning (Time Series Data)**

**[⬆ back to top](#table-of-contents)**

## **Section 13: Data Engineering**

**[⬆ back to top](#table-of-contents)**

## **Section 14: Neural Networks: Deep Learning, Transfer Learning and TensorFlow 2**

**[⬆ back to top](#table-of-contents)**

## **Section 15: Storytelling + Communication: How To Present Your Work**

**[⬆ back to top](#table-of-contents)**

## **Section 16: Career Advice + Extra Bits**

**[⬆ back to top](#table-of-contents)**

## **Section 17: Learn Python**

**[⬆ back to top](#table-of-contents)**

## **Section 18: Learn Python Part 2**

**[⬆ back to top](#table-of-contents)**

## **Section 19: Bonus: Learn Advanced Statistics and Mathematics for FREE!**

**[⬆ back to top](#table-of-contents)**

## **Section 20: Where To Go From Here?**

**[⬆ back to top](#table-of-contents)**

## **Section 21: Extras**

**[⬆ back to top](#table-of-contents)**

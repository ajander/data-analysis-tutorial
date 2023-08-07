# Data Analysis Tutorial Outline

## Pre-Work

Set up Python environment: VSCode, Python, virtual environment (? - maybe save setting up virtual environment for later)

Set up Github account and initialize a repo

## Exploratory Data Analysis

Use Google Colab Jupyter Notebook interface

### Python Basics

Data types, control structures, functions, program flow

Only include what we'll actually need for the analysis/modeling

### Pandas Basics

Examples of topics to cover…
* https://pandas.pydata.org/docs/getting_started/index.html
* https://www.w3schools.com/python/pandas/pandas_getting_started.asp
* https://www.datacamp.com/tutorial/pandas

### Explore Dataset

Read in data, exploratory statistics, exploratory plots (Seaborn?)

## Predictive Modeling (?)

Still with Google Colab

### Theory

Features and target

Train and test datasets

### Create Model

Fitting, predicting, and evaluating

Predicting on new data

Saving and loading trained model

## Using an IDE

Use VSCode or other IDE for this part.

### IDE Basics

Create and activate a virtual environment (if not done already)

How to run code

How to install libraries

Create requirements.txt

Move code over from Colab notebook

### Git Basics

git status, git add, git commit, git push

Commit code

## Dashboard

Still in IDE

Install Streamlit

### Streamlit Basics

* Resource: https://www.youtube.com/watch?v=_Um12_OlGgw&ab_channel=M%C4%B1sraTurp 
* Layout
  * Sidebar
  * Containers, columns
  * Expanders
* Text formatting
  * Title, header, subheader, text
* Data table, plotting
* User input
* Caching
* Session state and session callbacks

### Build Dashboard

Dataset description (with some statistics and plots from EDA section)

Predictive model: Take in a new datapoint from the user and deliver a prediction

### Deploy Dashboard

Deploy the Streamlit app using [Streamlit Community Cloud](https://docs.streamlit.io/streamlit-community-cloud/get-started/deploy-an-app)

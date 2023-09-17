<h1 align="center">French car Project</h1>

<p align="center">
This repository contains a project with the car labelling dataset from the french Ecological Transition Agency (ADEME). This project is part of the Data Scientist nanodegree by Udacity. The dataset was updated in september 2023. 
<br>
  <a href="https://www.udacity.com/course/data-scientist-nanodegree--nd025?campaign_name=back2skills&coupon=BACK2SKILLS&utm_source=gsem_brand&utm_medium=ads_r&utm_campaign=19167921312_c_individuals&utm_term=143524475679&utm_keyword=data%20science%20udacity_e&gclid=CjwKCAjwrranBhAEEiwAzbhNtU2AhXMTLOAIxbb7dFpKJJ5RpY5AJ2vrr2QDXU5EzU5AiBIidf2R_hoCqrYQAvD_BwE"><strong>Udacity nanodegree</strong></a>
  <br>
  <a href="https://medium.com/@guillaume.david11/find-the-right-price-for-your-new-car-model-757cda7ebe95"><strong>My blog post</strong></a>
  <br>
</p>

## Table of contents

- [How to run the project](#How-to-run-the-project)
- [Motivation and goals](#Motivation-and-goals)
- [Structure](#Structure)
- [Author and acknowledgement](#author-and-acknowledgement)

## How to run the project

Here is the list of installed packages for this project and how to run the project:


Clone the GitHub repository and use Python 3.11.

    $ git clone https://github.com/DavidGuillaum/project_french_car.git

In addition This will require pip installation of the following:

     pip install pandas
     pip install matplotlib
     pip install numpy
     pip install seaborn
     pip install request
     pip install scikit-learn


1. Just open the project_french_car.ipynb file and run the cells.


## Motivation and goals

The goals of this project is to create a predictive model that can give a price of a car with given feature. The prediction will be based on the actual french car market. This prediction could be usefull to find the price a new model for a car producer for example. Here is the list of the steps:
- I. Data
    - I decide to use an API as the dataset is udpated in time so the analysis will also be updated
- II. Cleaning
    - Drop useless columns and the last row
    - Take care of NaN values
    - Convert to the appropriate format
    - Take care of Duplicates
    - Look at the categorical values and take care of it when needed
- III. EDA
    - The goal of this project isn't to represent the french car market so I only represented distributions of variables and correlations
- IV. Price Prediction Model Training
    - I trained 3 model (Linear Regression, RidgeCV and LassoCV) to pick up the best one


## Structure
This project is structure is the following:

- project_french_car.ipynb #main file where the analysis will be done

- README.md

- data
    - ADEME - Car Labelling - Lexique des données - 2021-03.pdf #explanation of all variables (in french)



<br>


## Author and acknowledgement
I'm David Guillaume, currently studying for a master's degree in Data Analytics and Economics at the University of Fribourg (Switzerland). I'm very interested in data sciences, and economics in particular (bachelor's degree in Political Economy). I hope you'll like my project. I would like to thank Udacity for overseeing this program.
<br>
<a href="https://www.linkedin.com/in/david-guillaume-a7bb1b201/"><strong>Here is my Linkedin</strong></a>
<br>
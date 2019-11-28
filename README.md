# Stackoverflow 2019 survey results
 (Udacity DSND Project: Write a Data Science Blog Post)

## Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)


## Installation <a name="installation"></a>

This project requires Python 3.7, Numpy, Matplotlib, Pandas and Scikit-learn. I used the Anacaconda Miniconda distribution running on Windows for my environment but other setups should work fine if you install all the libraries found in the [requirements.txt](requirements.txt) file.

Download the full dataset for 2019 from [here](https://insights.stackoverflow.com/survey) into the data sub-folder and unzip.


## Motivation <a name="motivation"></a>

This project is intended to explore the 2019 stackoverflow survey results and answer some interesting questions about the data. The 3 main questions are

1. Who is the typical coder? (What are their attributes?)
2. What makes data scientists stand out? (Can we predict which developers are data scientists?)
3. Is Data Science inclusive? (Can we see more diversity compared with other developer roles)

The CRISP-DM process was followed to answer each question.

1. Business understanding
2. Data understanding
3. Data preperation
4. Modelling
5. Evaluation
6. Deployment

A summary of the findings are posted on [Medium](https://medium.com/@adeacon/who-are-data-scientists-c5a4f09fdb4c). Full details are in the code as described below.


## File descriptions <a name="files"></a>

Each question has it's own Jupyter notebook

* [Q1 Typical Coder](Q1_Typical_Coder.ipynb)
* [Q2 Data Scientist classifier](Q2_Data_Scientist_classifier.ipynb)
* [Q3 Data Scientist diversity](Q3_Data_Scientist_diversity.ipynb)


## Results <a name="results"></a>

A brief summary of the results...

1. Coders actually aren't all identical. No set of answers appeared more than 15 times out of 88,000+ responses. If we just look at data scientists we find that no set of answers appears more than once!

2. Data Scientists aren't that different from other developers. Or at least not enough that we can accurately predict which developers are data scientists based on their other responses.

3. Data Science is more diverse than other development roles. Not by a lot but there is a measurable difference: 44% of data scientists are NOT white heterosexual men as opposed to 40% of all other developers. If we look at the number of different diversity groups we find that they are represented over 4 times more frequently within the data scientist field (1 in 24 vs 1 in 109).


## Licensing, Authors, Acknowledgements <a name="licensing"></a>

Acknowledgement to Stack Overflow for sharing the dataset. Thanks also to my course mentor [NicoEssi](https://github.com/NicoEssi) for his advice and support. The code is available to use as you would like.
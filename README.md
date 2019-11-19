# Stackoverflow 2019 survey results
 (DSND Project: Write a Data Science Blog Post)

## Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)


## Installation <a name="installation"></a>

This project uses Python 3.7, Pandas, Scikit-learn and Jupyterlab. I used the Anacaconda Miniconda distribution running on Windows for my environment management but other setups should work fine if you install all the libraries found in the [requirements.txt](requirements.txt) file.

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

A summary of the findings will be posted on Medium. Full details are in the code as described below.


## File descriptions <a name="files"></a>

Each question has it's own Jupyter notebook

* [Q1 Typical Coder](Q1_Typical_Coder.ipynb)
* [Q2 Data Scientist clasifier](Q2_Data_Scientist_classifier.ipynb)
* [Q3 Data Scientist diversity](Q3_Data_Scientist_diversity.ipynb)


## Results <a name="results"></a>

A brief summary of the results...

1. Coders actually aren't all identical. No set of answers appeared more than 15 times out of 88,000 reposes.

2. Data Scientists aren't that different from other developers.

3. Data Science is a bit more diverse than other develpment roles


## Licensing, Authors, Acknowledgements <a name="licensing"></a>

Acknowledgement to Stack Overflow for sharing the dataset. Thanks also to my course mentor [NicoEssi](https://github.com/NicoEssi) for his advice and support. The code is available to use as you would like.
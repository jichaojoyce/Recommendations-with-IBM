# Recommendations-with-IBM Project

![Intro Pic](BIM.png)

## Table of Contents
1. [Description](#description)
2. [Getting Started](#getting_started)
	1. [Libraries](#library)
	2. [Installing](#installing)
	3. [Instruction](#executing)
	4. [Data distribution](#material)
3. [Authors](#authors)
4. [License](#license)
5. [Acknowledgement](#acknowledgement)
6. [Example](#screenshots)

<a name="descripton"></a>
## Description

This Project is part of Data Science Nanodegree Program by Udacity in collaboration with BIM Watson Studio platform.
The initial dataset contains users information on the articles recommendation. 
This project is aim to analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles they will like.

The Project contains two files:

1. 'Recommendations_with_IBM.ipynb'. The Jupyter notebook aims to (1) explore the article data; (2) compute user interactions; (3) deal with 'cold start problem': for new users, make recommendations based on the popular content; (4) use the SVD (singular value decomposition) model to build out a matrix decomposition and predict new articles an individual may interact with.  
2. 'Recommendations_with_IBM.html'. The html version of the 'Recommendations_with_IBM.ipynb' Jupyter notebook. 

<a name="getting_started"></a>
## Getting Started

<a name="dependencies"></a>
### Libraries
* Machine Learning Libraries: NumPy, Pandas
* Database Libraqries: pickle, project_tests
* Web App and Data Visualization: matplotlib.pyplot
<a name="installing"></a>
### Installing
Clone this GIT repository:
```
https://github.com/jichaojoyce/Disaster-classsifier-.git
```
<a name="Instruction"></a>
### Instructions:
1. Run the following commands in the project's root directory to set up your database and model.

    - To run ETL pipeline that cleans data and stores in database
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/disease.db`
    - To run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/disease.db models/classifier.pkl`

2. Run the following command in the app's directory to run your web app.
    `python run.py`

3. Go to http://0.0.0.0:3001/

### Data distribution:
The below figure is the distribution of message genres
![dis Pic](over.png)
The below figure is the distribution of categories
![dis Pic](categories.png)
<a name="authors"></a>
## Authors

* [Chao Ji](https://github.com/jichaojoyce)

<a name="license"></a>
## License
Feel free to use it!
<a name="acknowledgement"></a>
## Acknowledgements

Credicts give to [Udacity](https://www.udacity.com/).

<a name="screenshots"></a>
## Example

1. You can type a sentence for classify. Here I typed 'we are more than 50 people sleeping on the street. Please help us find food, tent.'

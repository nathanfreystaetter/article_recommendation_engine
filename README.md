# article_recommendation_engine

### Project Overview

This project analyzes the interactions that users have with articles on the IBM Watson Studio platform and makes recommendations to them about new articles that are relevant for them.

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.* The project leverages the following libraries:
    Pandas
    Numpy
    Matplotlib
    Pickle

## Project Motivation<a name="motivation"></a>

This project is part of Udacity's Data Science Nanodegree curriculum that touches on various recommendation engine practices, particularly SVD.

## File Descriptions <a name="files"></a>

All code and analysis can be found in the Recommendations_with_IBM.ipynb notebook. Other documents include

* data/user-item-interactions.csv: Csv file with user-item interactions.
* data/articles_community.csv: Csv file with indexed items.


## Results<a name="results"></a>

The final proposal shows that accuracy increases as latent features increase. However, there is reason to believe there is an overfitting problem, which is likely occuring since the number of users that fall in the train and test data sets are limited, with only 20 such users. For this reason, other recommmendation methods should be leveraged to improve our recommendation, particularly collaborative filtering or content based recommendation engines.**

That being said, we could run an A/B test to determine how well this recommendation engine performs to increase the time spent or number of articles read on the platform relative to current treatment

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Thanks to the Udacity program and IBM for providing lessons and data to perform this project.

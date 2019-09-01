
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

This project utilizes default packages within the Anaconda distribution of Python for the majority of the analysis. 

However, you will need to install plotly if you haven't already done so before. See [Getting Started with Plotly for Python](https://plot.ly/python/getting-started/).

In addition, if you would like to display the plotly visualizations within the jupyter notebook, then you will need to install the orca commandline utility and the psutil and requests Python libraries. See [Static Image Export in Python](https://plot.ly/python/static-image-export/).

The code should run with no issues using Python versions 3.*.


## Project Motivation<a name="motivation"></a>

For this project, I was interestested in using Seattle Airbnb data to better understand:

1. What are the distribution of listing prices by neighborhoods?
2. How varied are the neighborhoods in terms of property type?
3. How well can we predict listing price?


## File Descriptions <a name="files"></a>

There are 3 notebooks available here to showcase work related to the above questions.  Each of the notebooks is exploratory in searching through the data pertaining to the questions showcased by the notebook title.  Markdown cells were used to assist in walking through the thought process for individual steps.  

There is an additional `.py` file that runs the necessary code to obtain the final model used to predict salary.

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/p/3cb0df7699d3/edit).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>
Credit to Airbnb for providing the data. Licensing information can be found at the [Kaggle page](https://www.kaggle.com/airbnb/seattle) and the original source from [Airbnb Inside](http://insideairbnb.com/get-the-data.html).

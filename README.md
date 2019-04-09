# Udacity's Data Scientist Foundations Nanodegree
## Data Wrangling
## Project: Data Wrangling and Analysis of WeRateDogs Twitter Archive

## Project Overview

Real-world data rarely comes clean. The project is well designed to teach us three ways of data gathering. Using Python and its libraries, I gathered data from a variety of sources and in a variety of formats, assessed its quality and tidiness, then cleaned it. This is called data wrangling. The three modes of data gathering I used are downloading data directly, downloading data programmatically, and storing data using twitter APIs. Analysis and visualizations is done using Python (and its libraries) and SQL.

### Dataset
The dataset used for wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.
This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017.

![sample image of WeRateDogs from Twitter](Images/WeRateDogs.png)


### Softwares Required
* Jupyter Notebook

The following packages (libraries) need to be installed. You can install these packages via conda or pip.
* pandas
* NumPy
* requests
* tweepy
* json

### Project Instructions
1. Clone the repository and navigate to the downloaded folder.
  ```
  git clone https://github.com/adityasaxena26/Data-Wrangling-and-Analysis-of-WeRateDogs-Twitter-Archive.git
  cd Data-Wrangling-and-Analysis-of-WeRateDogs-Twitter-Archive
  ```
2. open wrangle_act.ipynb

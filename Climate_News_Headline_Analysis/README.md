# Climate News Headline - Sentiment Analysis
## Overview
Climate change is one of the most pressing issues of our time, and the way it's portrayed in the media can significantly influence public perception and policy. In this notebook, we'll dive into a dataset of climate change news headlines to uncover insights about the sentiment surrounding this critical topic.

## Dataset Used
***[Dataset](Climate_News_Headline_Analysis/climate_headlines_sentiment.csv)***

## Analysis Performed

1. Sentiment Distribution
2. Identifying Sentiment Patterns
3. Headline Analysis
4. Sentiment Trends by Themes based on Headline keywords
5. Measured Mean Square Error for the Sentiment Prediction

## Install Packages
To install the necessary packages, run the following commands:

```sh
pip install wordcloud
```
## Libraries
The Libraries used in this analysis:

```sh
import pandas as pd
import matplotlib.pyplot as plt
%matplotlib inline
```
```sh
import warnings
import seaborn as sns
from wordcloud import WordCloud
```
## Machine Learning Libraries
```sh
from sklearn.model_selection import train_test_split
from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.linear_model import LinearRegression
from sklearn.neighbors import KNeighborsRegressor
from sklearn.tree import DecisionTreeRegressor
from sklearn.ensemble import VotingRegressor
from sklearn.metrics import classification_report, accuracy_score, confusion_matrix
from sklearn.metrics import mean_squared_error
```

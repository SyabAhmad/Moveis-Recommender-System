# Movie Recommender System in Python
## Data used in this system 
https://www.kaggle.com/datasets/sankha1998/tmdb-top-10000-popular-movies-dataset?resource=download
###  you can download this dataset from kaggle website and start your practice.

```python

# Loading Data and importing important imports
import pandas as pd
import numpy as np

# Now loading data
movies = pd.read_csv("data/moviesData.csv")


# Data Pre-Processing started
# will display the data to check
print(movies.head())

```
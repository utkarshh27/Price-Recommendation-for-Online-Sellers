# Price-Recommendation-for-Online-Sellers
## Description- 
E-commerce platforms today are extensively driven by machine learning algorithms, right from quality checking and inventory management to sales demographics and product recommendations, all use machine learning. One more interesting business use case that e-commerce apps and websites are trying to solve is to eliminate human interference in providing price suggestions to the sellers on their marketplace to speed up the efficiency of the shopping website or app. That's when price recommendation using machine learning comes to play.
## Dataset Features

* ID: the id of the listing
* Name: the title of the listing
* Item Condition: the condition of the items provided by the seller
* Category Name: category of the listing
* Brand Name: brand of the listing
* Shipping: whether or not shipping cost was provided
* Item Description: the full description of the item
* Price: the price that the item was sold for. This is the target variable that you will predict. The unit is USD.

Dataset-source: https://www.kaggle.com/competitions/mercari-price-suggestion-challenge/data

# Import Packages

```
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import gc
import time
```
```
from scipy.sparse import csr_matrix, hstack
from sklearn.preprocessing import LabelBinarizer
from sklearn.feature_extraction.text import CountVectorizer, TfidfVectorizer
from sklearn.model_selection import train_test_split, cross_val_score
from sklearn.metrics import mean_squared_error
import lightgbm as lgb
```
# Visulization

![alt text](https://github.com/[username]/[reponame]/blob/[branch]/image.jpg?raw=true)

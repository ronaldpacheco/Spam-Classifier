# Spam Classifier

In this Spam Classifier Notebook, we:
* Read our raw data
* Parse our data
* Perform Exploratory Data Analysis on our parsed data
* Create new features from our parsed data
* Vectorize our data
* Try 3 different models, tune them and choose the best one
* Measure the predict time of our final model

## Packages used

```python
import nltk
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
plt.style.use('ggplot')
import seaborn as sns
import re
import string
from sklearn.feature_extraction.text import CountVectorizer, TfidfVectorizer
from sklearn.model_selection import train_test_split, cross_validate, GridSearchCV
from sklearn.pipeline import make_pipeline
from scipy import stats
from sklearn.preprocessing import StandardScaler
from time import time
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Data Source
https://files3.lynda.com/secure/courses/622075/exercises/Ex_Files_NLP_Python_ML_EssT.zip?RSpHhLLzXzW0MdMBSf6BmhHggoanAQsucD7GUAOwRGjGIxbQCvNPITpBRJ8c11cxm3RWxCNuYBCUuY3qXaOcFYFM0zQVjc3VXMe0SAW1g1Ptu9V-1RWKdgF9TIqUolGSE0JO830M0vx7Yide7Dd60WFlDxmhVgO7-0VxDaHe

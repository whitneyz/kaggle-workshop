# kaggle-workshop


#### Steps

1. Install [Python](https://realpython.com/installing-python/) (No not the :snake:)




#### Colab

A free platform from Google that allows users to code in Python. Colab is essentially the Google Suite version of a Jupyter Notebook.

##### Importing libraries
1. log into your Google Account and go to Google Drive
2. Click on the New button on the left and select Colaboratory if it is installed (if not click on Connect more apps, search for Colaboratory and install it)
3. import libraries
 ```
 import pandas as pd
from matplotlib import pyplot as plt
%matplotlib inline
import seaborn as sns
```

#### Importing dataset by uploading CSV from GitHub repository

1. Click on the dataset in the repository (source)
2. Click on Raw
3. Copy the link to the raw dataset and store it as a string variable called url in Colab
4. df is 
```
url = 'copied_raw_GH_link'
df = pd.read_csv(url)
``

#### Jupyter Notebook

 - Install [Jupyter](https://jupyter.readthedocs.io/en/latest/install/notebook-classic.html)
 - Run [Jupyter Notebook](https://jupyter.readthedocs.io/en/latest/install/notebook-classic.html)

#### Pandas

#### Dictionary :open_book:
Kernels = Kaggle's public analisys by people about the datasets



#### Have fun :grinning:


![](https://giphy.com/gifs/titanic-k-ok-n-4ryp9Ihw0BEyc)
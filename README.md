import numpy as np
import pandas as pd 
import matplotlib.pyplot as plt
import seaborn as sns

df_movie=pd.read('IMDb Movies India-csv',sep="::",engine='Python')
df_movie.dropna(inplace = True)
df_movie.head()

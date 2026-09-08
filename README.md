# odobairegiovanni
covid-analysis-odobairegiovanni

# 
from google.colab import drive

drive.mount('/content/drive')
import pandas as pd
df = pd.read_csv('/content/drive/MyDrive/epidemiology.csv')
print(df.shape)
df.head()

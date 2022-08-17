# Datasets_for_practice

### Use The Code Below in .ipynb or .py file to load the dataset


import pandas as pd

url = 'https://raw.githubusercontent.com/amitrangwal/Datasets_for_practice/main/titanic.csv'

r = requests.get(url, allow_redirects=True)

open('titanic.csv', 'wb').write(r.content)

titanic=pd.read_csv('titanic.csv')

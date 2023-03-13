## Shortcut to fetch data 

url = 'https://raw.githubusercontent.com/vkoul/data/master/misc/'     

data = "datafilename.csv"

complete data = url + data

**Sample**

```py 

import pandas as pd

url = 'https://raw.githubusercontent.com/vkoul/data/master/misc/' 

# data to be used = car_data.csv

df = pd.read_csv(url + "car_data.csv")

df.head()

```

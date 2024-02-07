import pandas as pd
people=['kiran','ajay','vijay','varun']
age=[25,30,35,26]
height=[145,151,165,173]
weight=[45,55,65,75]
data={
    "name":people,
    "age":age,
    "height":height,
    "weight":weight,
}
df=pd.DataFrame(data)
print(df)

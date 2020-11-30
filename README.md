# ByteWizards_Data_Analytics_Project_2020
Semester-5 project for Data Analytics(UE18CS312)


## How to read the pickled data
```
import pickle
pickle_in = open("CleanedDataAnalyst.pickle", "rb")
df = pickle.load(pickle_in)
pickle.close()

df.head()
```

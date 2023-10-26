import pandas as pd

df = pd.read_csv("survey_results_public.csv", index_col="WorkExp") # Indexing specific column
df[["WebframeWantToWorkWith", "ConvertedCompYearly", "Age"]].head(100)   # Take the first 100 rows of the data with specified columns


print(df.WorkExp.median())  # AVG working experience
print(df.ConvertedCompYearly.max())   #Max salary
print(df.WorkExp.min()) #Min Working experience



print(df.WorkExp.median())  # AVG working experience
print(df.ConvertedCompYearly.max())   #Max salary
print(df.WorkExp.min()) #Min Working experience

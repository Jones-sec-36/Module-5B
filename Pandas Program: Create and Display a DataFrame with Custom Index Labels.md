# Pandas Program: Create and Display a DataFrame with Custom Index Labels

## 🎯 Aim

To create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows.

---

## 🧠 Algorithm

1. **Import Libraries**: Import the required libraries – `pandas` and `numpy`.
2. **Create Dictionary**: Define a dictionary `exam_data` with keys: `'name'`, `'score'`, `'attempts'`, and `'qualify'`.
3. **Index Labels**: Create a list of custom index labels called `labels`.
4. **Create DataFrame**: Use `pd.DataFrame()` to create the DataFrame by passing the dictionary and index labels.
5. **Display Output**: Display the DataFrame using `print()` or by simply calling the DataFrame variable.

---

## 💻 Program
```
import pandas as pd
import numpy as np
d=eval(input())
l=eval(input())
df=pd.DataFrame(d)
print("Original Dataframe")
print("",df)
print("combined Dataframe")
l1=pd.DataFrame([l],columns=df.columns)
df1=pd.concat([df,l1],ignore_index=True)
print("",df1)
```

## Output
<img width="1415" height="779" alt="image" src="https://github.com/user-attachments/assets/55f333c2-1390-4cea-addf-520e6a577373" />

## Result
Thus, the program has been executed successfully.

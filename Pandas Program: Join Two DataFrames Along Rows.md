# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program
```
import pandas as pd 
d1 = pd.DataFrame(eval(input()))
d2 = pd.DataFrame(eval(input()))
print("Original DataFrames:")
print(d1)
print("-------------------------------------")
print(d2)
print("\nJoin the said two dataframes along columns:")
result = pd.concat([d1,d2],axis=1)
print(result)
```

## Output

<img width="1544" height="824" alt="image" src="https://github.com/user-attachments/assets/90d14873-c9f2-414f-8a22-3cfda8eb53d9" />

## Result
Thus, the program has been executed successfully.

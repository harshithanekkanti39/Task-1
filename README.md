# Task-1 Data Cleaning & Preprocessing (AI/ML Internship)

##  Objective
Clean, preprocess, and analyze the given dataset for machine learning tasks.

##  Dataset Used
- student-mat.csv (Student Performance Dataset)

##  Steps Performed
1. Imported and explored the dataset  
2. Checked for missing values  
3. Handled null values using median/mode  
4. Encoded categorical features  
5. Standardized numerical columns  
6. Detected & visualized outliers  
7. Removed extreme outliers using IQR  
8. Saved the cleaned dataset  

##  Tools Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

##  Files in Repository
- `student-mat.csv` — raw dataset  
- `task_2.py` — preprocessing code  
- `README.md` — documentation  

## How to Run(Google colab)

1. Open Google Colab: https://colab.research.google.com
2. Upload the notebook or Python file:
   - Click on File → Upload Notebook / Upload File
3. Upload the dataset `student-mat.csv` into the Colab session:
   - Click on the folder icon (left side)
   - Click the upload button and choose the CSV file
4. Run each code cell step-by-step.
5. The cleaned dataset and visualizations will be generated inside Colab.

Note:
If you want to load the dataset directly from GitHub, use this:

import pandas as pd
url = "https://raw.githubusercontent.com/harshithanekanti39/Task-2/main/student-mat.csv"
df = pd.read_csv(url)

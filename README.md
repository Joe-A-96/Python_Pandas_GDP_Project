# Python Pandas – Skills Overview
Based on the GDP per Capita Analysis Notebook

## Importing Core Libraries
- Importing pandas for data manipulation  
- Importing matplotlib and seaborn for data visualization  
- Understanding why libraries must be imported before use  

---

## Loading and Inspecting Data
- Reading CSV data using `pd.read_csv()`  
- Inspecting data using:  
  - `df.head()`  
  - `df.tail()`  
  - `df.info()`  
  - `df.describe()`  
  - `df.shape`  
  - `df.columns`  
- Understanding dataset structure, column names, and data types  
<img width="881" height="256" alt="image" src="https://github.com/user-attachments/assets/955f8330-22fd-4224-b60e-df606f5f096f" />

---

## Handling Missing and Null Values
- Checking for missing values using `df.isnull().sum()`  
- Filling missing values using `df.fillna()`  
- Removing missing values using `df.dropna()`  
- Using `value_counts()` to inspect categorical inconsistencies  
- Identifying columns stored as incorrect data types  
<img width="244" height="341" alt="image" src="https://github.com/user-attachments/assets/a5e3aa70-e7d9-4a69-97ca-7e424df7cee5" />

---

## Data Cleaning and Transformation
- Converting columns to numeric or appropriate data types  
- Replacing placeholder values (such as zeros) with meaningful values  
- Renaming and reorganizing columns for clarity  
- Filtering rows using Boolean conditions  
- Standardizing inconsistent category labels  

---

## Exploratory Data Analysis (EDA)
- Reviewing distributions and summary statistics  
- Identifying unusual or inconsistent values  
- Investigating frequent values and patterns  
- Using `groupby()` to calculate aggregated metrics  
- Exploring questions such as:  
  - Why is a column stored as an object?  
  - Which regions or countries have the highest GDP per capita?  
<img width="543" height="315" alt="image" src="https://github.com/user-attachments/assets/8c58096c-d149-4042-ad59-ebc853bb54fa" />

---

## Outlier Detection
- Identifying outliers using statistical measures  
- Detecting outliers visually with:  
  - Histograms  
  - Boxplots  
- Investigating extreme or unusual values within population or GDP estimates  
<img width="862" height="741" alt="image" src="https://github.com/user-attachments/assets/fb7596ba-76dd-4904-b641-8c642ed6d58a" />

---

## Data Visualization
- Visualizing numeric distributions using histograms  
- Visualizing data spread using boxplots  
- Visualizing categorical distributions using bar or count plots  
- Adjusting titles, labels, and layout using matplotlib  

---

## Analytical Thinking and Workflow
- Formulating meaningful data questions  
- Inspecting unusual values and missing patterns  
- Structuring a clear analysis workflow  
- Documenting work using Markdown in Jupyter Notebook  

---

## Summary
This notebook demonstrates skills in:  
- Data loading and inspection  
- Data cleaning and transformation  
- Handling missing values  
- Filtering, grouping, and aggregating data  
- Outlier detection  
These represent essential skills needed for effective data analysis using Python and Pandas.

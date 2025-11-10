

#  Google Search Data Analysis 

A complete data analysis project performed in **Google Colab** using an **Excel (.xls/.xlsx) dataset**.
This project includes data uploading, cleaning, preprocessing, encoding, visualization, and exporting the final cleaned dataset.

---

##  Project Overview

This project demonstrates a full data-analysis workflow on a Google Search dataset using **Python in Google Colab**.
It includes:

* Uploading Excel data
* Exploring dataset structure
* Cleaning missing & inconsistent values
* Handling categorical and numerical features
* Extracting features from date columns
* Encoding data
* Scaling numeric features
* Splitting into train/test sets
* Visualizing trends (bar, pie, line, scatter)
* Exporting cleaned data back to Excel

This project is designed for **beginners**, **students**, and **data-analysis learners**.

---

##  Files Include 
data_export_cleaned

---

##  Technologies Used

* **Python**
* **Google Colab**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Scikit-Learn**


##  How to Use

### Step 1: Open Google Colab

Open the notebook in Google Colab by clicking:
File → Upload Notebook  
Or drag-and-drop.

### Step 2: Upload Your Excel File

The first code cell will prompt you to upload:

```python
from google.colab import files
uploaded = files.upload()
Upload your `.xls` or `.xlsx` file

### Step 3: Run All Cells

Simply run:
Runtime → Run all

This will perform all:

* Cleaning
* Transformations
* Encoding
* Visualizations
* Train-test split
* Export

##  Visualizations Include

* Bar Plot
* Pie Chart

##  Data Cleaning Steps

✔ Remove extra spaces
✔ Fix inconsistent data types
✔ Fill missing numeric values with **median**
✔ Fill missing categorical values with **mode**
✔ Detect & extract **year, month, day** from date columns
✔ Convert categorical data using Label Encoding
✔ Scale numeric values using StandardScaler

##  Machine Learning Preparation

The dataset is automatically checked for:
* `target`, `label`, `y`, `outcome`, `survived`
If found → train/test split
If not → index-based random split


##  Exporting Results

The cleaned file is automatically saved 
data_export_cleaned.xlsx
and downloaded to your system.




If you want, I can **generate this as a README.md file** for download.

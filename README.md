# SCT_DA_2
Task 2 - Data Cleaning and Preparation using Python &amp; Pandas

# SkillCraft Technology - Data Analytics Internship
## Task 02: Data Cleaning and Preparation 🧹💻

**Repository:** `SCT_DA_2`

### 📝 Project Objective
Load a raw dataset ("Global Superstore") into a Python environment using the Pandas library, identify and handle missing values, drop duplicate rows, convert data types (string columns to proper date format), and export the cleaned dataset into a new CSV file.

### 🛠️ Tech Stack & Tools
* **Language:** Python
* **Library:** Pandas
* **Environment:** Google Colab / Jupyter Notebook

### ⚙️ Steps Performed in Python
1. **Data Loading:** Imported the raw dataset using `pd.read_csv()` with appropriate encoding (`latin1`).
2. **Missing Value Treatment:** Checked for null values across all columns and securely handled them (e.g., filling missing Postal Codes with 'Unknown').
3. **Duplicate Removal:** Dropped redundant rows using `.drop_duplicates()` to ensure data integrity and consistency.
4. **Data Type Conversion:** Converted `Order Date` and `Ship Date` columns from string/object format to proper `datetime` objects for time-series operations.
5. **Data Export:** Successfully exported the cleaned and structured dataset into a new CSV file (`Cleaned_Global_Superstore_Task2.csv`).

### 📂 Files in this Repository
* `Untitled2.ipynb`: Complete Python script containing the step-by-step data cleaning pipeline.
* `Cleaned_Global_Superstore_Task2.csv`: The final processed and cleaned dataset.

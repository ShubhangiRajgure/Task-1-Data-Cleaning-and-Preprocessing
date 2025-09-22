# Task1-Data-Cleaning-and-Preprocessing
# Medical Appointment No. Shows – Data Cleaning

## 📌 Overview
This project focuses on cleaning the **Medical Appointment No. Shows** dataset using **Python (pandas)** as a tool 
and **Jupyter Notebook** as a resource.  
The dataset originally contained duplicates, inconsistent formats, and invalid values.  
I applied several cleaning steps to prepare it for further analysis.

---

## Data Cleaning Steps
1. **Handled Missing Values**  
   - Checked for and handled missing values.
     
2. **Removed Duplicates**  
   - Checked for and dropped duplicate rows.

3. **Handled Invalid Ages**  
   - Removed rows where `Age` < 0 or `Age` > 120.

4. **Datetime Conversion**  
   - Converted `ScheduledDay` and `AppointmentDay` into proper datetime objects.

5. **Standardized Categorical Values**  
   - Converted `Gender` values to uppercase (`M`, `F`).  
   - Converted `No-show` values to uppercase (`YES`, `NO`).  

6. **Renamed Columns**  
   - Fixed spelling: `Handcap` → `Handicap`.

---

## Output Files
- **`Medical-Appointment-No-Shows-Clean.csv`** → Cleaned dataset.  
- **`Data_Cleaning_Report.txt`** → Detailed summary of cleaning process (shape before/after, duplicates, invalid ages, sample preview).  

- Standardized categorical values  


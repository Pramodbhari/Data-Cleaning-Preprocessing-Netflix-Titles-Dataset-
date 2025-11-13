# 🎬 Task 1 – Data Cleaning & Preprocessing (Netflix Titles Dataset)

This repository contains my solution for **Task 1** of the Elevate Labs Data Analyst Internship — performed on the **Netflix Titles Dataset**.

---

## 📁 Dataset
The dataset used: **netflix_titles.csv**  
Contains information about Movies and TV Shows available on Netflix.

---

## 🧼 Cleaning Steps Performed

### 1. **Data Loading & Inspection**
- Viewed top records
- Checked shapes and data types
- Created backup of raw data

### 2. **Handling Missing Values**
- Removed blank text values (`director`, `cast`, `country`) 
- Cleaned `date_added` by converting to datetime

### 3. **Removed Duplicates**
- Used Excel to remove duplicate rows

### 4. **Standardized Text Columns**
- Converted text to lowercase
- Removed leading/trailing spaces
- Standardized category names such as “Movie” and “TV Show”

### 5. **Date Formatting**
- Converted `date_added` to standard **YYYY-MM-DD**
- Extracted new column `year_added`

### 6. **Renamed Columns**
- Converted all column names to lowercase and replaced spaces with underscores

### 7. **Data Type Correction**
- `release_year` → integer
- `date_added` → datetime
- `duration` → split into numeric + type (min / season)

---

## 🧰 Tools Used
- **Excel** for filtering, formatting, and basic cleaning   

---

## 📦 Repository Contents
| File | Description |
|------|-------------|
| netflix_titles.csv | Raw dataset uploaded |
| netflix_titles.csv | Cleaned dataset |
| README.md | Documentation |

---

## 🚀 Summary
This task demonstrates skills in:

- Missing value treatment
- Duplicate removal
- Text standardization
- Date cleaning
- Dataset exporting

The dataset is now **clean, structured, and ready for analysis**.

---


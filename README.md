# Task 1 - Data Preprocessing

This repository contains a preprocessed version of the dataset. The raw dataset is from the [Inventory Analysis Case Study](https://www.kaggle.com/datasets/bhanupratapbiswas/inventory-analysis-case-study) on Kaggle.

## Dataset Overview

The `preprocessed_data.zip` file includes the cleaned and prepared dataset, which was initially extracted and processed from the raw data.

### Steps Taken for Data Preprocessing

1. **Dataset Extraction**  
   I downloaded the dataset from Kaggle and extracted the files from the `.zip` archive.

2. **Merging Multiple CSV Files**  
   The dataset contained 5 separate CSV files. I merged all the files into one unified dataset to facilitate further analysis.

3. **Handling Missing and Duplicate Values**  
   - Removed rows with missing (null) values using the `drop` function.
   - Checked for and removed any duplicate rows to ensure data integrity.

4. **Data Cleaning**  
   During the cleaning process, I identified two columns, **"SIZE"** and **"VOLUME"**, that had similar functionality. After reviewing the data, I decided to drop one of these columns to reduce redundancy.

5. **Preprocessed Dataset**  
   The final cleaned and merged dataset is available in the `preprocessed_data.zip` file.

## Conclusion

These steps were followed to clean and preprocess the dataset, making it ready for analysis or further tasks.

---
Feel free to reach out if you have any questions or need further clarifications.

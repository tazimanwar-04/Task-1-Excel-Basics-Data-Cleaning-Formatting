Task 1: Excel Data Cleaning & Formatting

## Dataset
The dataset used for this task was downloaded from Kaggle. It is the **Netflix Movies and TV Shows** dataset, provided in CSV format. The dataset contains details such as title, type, director, cast, country, release year, rating, duration, and description of Netflix content.

---

## Tools Used
- Microsoft Excel  
- Kaggle (for downloading the dataset)

---

## Data Cleaning Process

First, the dataset was opened in Microsoft Excel and checked to ensure that the first row contained proper column headers. The original file was saved separately as `Raw_Data.xlsx` to keep the raw data unchanged.

To make analysis easier, the header row was frozen so that column names remained visible while scrolling. Filters were applied to each column to check for missing values. Blank cells were identified column by column and highlighted using conditional formatting for better visibility.

A new sheet named `Cleaned_Data` was created, and all cleaning operations were performed on this sheet to maintain a clear separation between raw and processed data.

Extra spaces in text-based columns such as title, director, cast, country, and listed_in were removed using the TRIM function. Text formatting was standardized wherever necessary. Duplicate records were removed using the Remove Duplicates option by expanding the selection so that complete rows were considered.

Date and categorical columns were reviewed to ensure consistency. A column named `Data_Quality_Notes` was added to document any data-related observations. Since no major issues required documentation, this column was left blank.

Finally, the cleaned dataset was saved as `Cleaned_dataset.xlsx` and exported as `cleaned_dataset.csv`.

---

## Files Included
- `Raw_Data.xlsx` – Original dataset  
- `Cleaned_dataset.xlsx` – Cleaned dataset  
- `cleaned_dataset.csv` – CSV version of the cleaned data  

---

## Outcome
This task helped me understand the basics of data cleaning in Excel, including handling missing values, formatting inconsistencies, and duplicates, while following a structured and professional data preparation workflow.

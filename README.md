# UCI Online Retail Data Analysis Using Pandas

## Project Overview

This project explores the UCI Online Retail dataset using Python and Pandas. The goal is to practice data inspection, data cleaning, data transformation, and sales analysis using real-world retail transaction data.

## Dataset

- **Source:** [UCI Machine Learning Repository — Online Retail](https://archive.ics.uci.edu/dataset/352/online+retail)
- **Data type:** Online retail transactions
- **Original dataset size:** 541,909 records and 8 columns
- **Time period:** December 2010 to December 2011

## Tools and Technologies

- Python
- Pandas
- Jupyter Notebook
- Excel/CSV

## Tasks Performed

1. Displayed the first 10 rows.
2. Checked the number of rows and columns.
3. Inspected column names and data types.
4. Counted missing values.
5. Identified duplicate records.
6. Counted unique customers.
7. Identified frequently appearing products.
8. Calculated revenue using Quantity × UnitPrice.
9. Calculated revenue by country.
10. Identified the top 10 countries by revenue.
11. Extracted year and month from invoice dates.
12. Analyzed transactions with negative quantities.
13. Counted unique invoices.
14. Analyzed monthly revenue.
15. Cleaned and exported the dataset to CSV.

## Key Learning Outcomes

- Understanding the structure of real-world data.
- Using Pandas for data inspection and cleaning.
- Applying filtering, grouping, sorting, and aggregation.
- Working with date and time columns.
- Calculating revenue and analyzing sales trends.
- Exporting processed data to CSV.

## How to Run the Project

1. Download the dataset from the official UCI source.
2. Install the required Python libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Open `Online_Retail_Analysis.ipynb` in Jupyter Notebook.
4. Update the dataset path if necessary.
5. Run the notebook cells from top to bottom.

## Notes

- Missing customer IDs are retained unless a specific analysis requires customer information.
- Negative quantities may represent product returns or cancellations.
- Revenue calculated as Quantity × UnitPrice may include negative transaction values.
- Results should be interpreted according to the cleaning and analysis rules used.

https://github.com/NavinkData/retail/blob/main/Screenshot%202026-10-14%20171925.png

## Author

Navin Kumar Singh

GitHub: [NavinkData](https://github.com/NavinkData)

**Task- Cleaning the Messy Data**

This task involved cleaning a raw CSV file using Python (Pandas) to prepare it for further data analysis.

**Cleaning Steps Performed:**

**1.String Cleaning:**

Removed leading/trailing spaces using .str.strip().

Standardized text formatting to Title Case using .str.title() (applied to Name and Department).

**2.Duplicate Removal:**

Removed duplicate records based on both Name and Department using drop_duplicates().

**3.Date Formatting:**

Converted the Join Date column from string to datetime format using pd.to_datetime().

Used errors='coerce' and dayfirst=True to handle inconsistent or invalid date formats.

**4.Salary Column Fixes:**

Removed commas from salary values using .str.replace().

Replaced "NaN" and "N/A" with 0.

Converted the Salary column to float.

Filled any remaining NaN values with 0.

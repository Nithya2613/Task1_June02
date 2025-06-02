Downloaded the "Vehicle Sales and Market Trends Dataset" from kaggle.
Imported necessary libraries like pandas and numpy for data handling.
Loaded the dataset using pandas.
Viewed basic information about the data such as column names, data types, and sample records.
Handled missing values by filling text columns with "unknown" and numeric columns with the median value.
Removed duplicate rows to avoid repetition.
Standardized text columns by converting them to lowercase and removing any extra spaces.
Converted the sale date to a standard format (dd-mm-yyyy).
Renamed column headers to be lowercase and removed spaces for consistency.
Fixed data types by converting columns like year, odometer, condition, etc., to numeric formats.
Detected and removed outliers in numeric columns to ensure clean and reliable data.
The final dataset is now cleaned and ready for further analysis or modeling.

# indian__census
Indian Census Data Analysis 

This Python script analyzes Indian census data to extract district-level and state-level insights related to population, religion, and workforce.

Features:

Hides dataframe indexes and sets a caption on the table.

Filters and displays records for selected districts: New Delhi, Lucknow, and Jaipur.

Calculates total population per state.

Calculates total population by different religions per state.

Counts the number of male workers in the state of Maharashtra.

Sets a specific column (District Code) as the index.

Adds a suffix to all column names for labeling or clarity.

Requirements:

Python

pandas

numpy

matplotlib

seaborn

How to Run:

Ensure the indiaCensus.csv file is downloaded on your system.

Update the file path in the script to match your file location. For example:
df = pd.read_csv("C:/Users/YourName/Downloads/indiaCensus.csv")

Run the script using Python:
python indian_census.py

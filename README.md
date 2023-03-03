# Survey taker job breakdown

Did a breakdown of survey takers' job using Power BI. Survey takers are data professional from around the world, but mostly in the USA.

Steps taken for this project;
1. Obtained the dataset in xlsx-type file
2. Performed extract, transform, load (ETL) process using Power Query in Power BI
  - Check for incorrect data type, if any
  - Removing duplicates, if any
  - Removing blank columns
  - Salary column is in ranges. Created 2 new columns, each for lower and higher limit of the range before proceeding to calculate the average in a new column
  - Those with "Other (Please specify)" were simplified to "Other"
  - Trim columns
3. Created dashboard to tabulate several KPIs of the data gathered

Observation:
  - *Salary* for Data Professionals are ***HIGHER*** in the USA and Europe compared to other countries in Africa, Asia, etc.
  - *Average salary's satisfaction* is suprisingly ***LOW*** despite the rumours that IT and Data Professionals makes a lot of money.
  - Data Scientist leads the way in the average salary category
  - Unsuprisingly, Python is the favourite programming language, followed by R

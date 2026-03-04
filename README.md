Phase 1 – Data Cleaning and Preparation

In Phase 1, I focused on cleaning and preparing the Titanic dataset to make it ready for analysis and modeling. The main steps were:

Read the dataset

Loaded the train.csv file into a Pandas DataFrame.

Handle missing values

Filled missing values in the Age column with the median age.

Filled missing values in the Embarked column with the most frequent port.

Remove duplicates

Dropped any duplicate rows to avoid repeated records.

Drop irrelevant columns

Removed the Cabin column because it contains many missing values and is not essential for this phase.

Handle outliers

Used the IQR (Interquartile Range) method to detect and clip extreme values in the Fare column.

Final checks

Verified that there are no missing values left.

Confirmed all Age values are non-negative.

Checked that the DataFrame now has the correct number of columns.

Result: The dataset is now clean, consistent, and ready for analysis in the next phases.

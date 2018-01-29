## You need to follow the steps

1. Download the data source file with the following link:

Visit the link for Human Activity Recognition Using Smartphones Data Set: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 
And for the data set of the project please us the following link: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

## Performing R Script

1. Analysis of Training and Test Data
a. Reading Training, Testing, Feature Vector, and Activity Label Tables
b. Assigning Column Names
c. Merging all Data Sets in one set

2. Extract Mean and Standard Deviation (SD) of each measurement
a. Reading Column Names
b. Create vectors for ID, Mean, and SD
c. Creating Subsets needed from setAllinOne

3. Use appropriate words to name the Activities in the data set
4. Use appropriate words to describe variable names
5. Create Tidy Data Set

## Variables Used

-x_train, y_train, x_test, y_test, subject_train and subject_test contain the data from the downloaded files.
-x_data, y_data and subject_data merge the previous datasets to further analysis.
-features contains the correct names for the x_data dataset, which are applied to the column names stored in

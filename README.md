# analysis.R
analysis.R script for Getting and Cleaning Data

# README
## run analysis on Human Activity recognition dataset.
## Dataset: Human Activity Recognition Using Smartphones
## Included Files
  * Codebook 2 versions:
    * CodeBook.md is a codebook created with R Markdown (RMD) using Knit. It describes the variables, data, and any transformations or work that I performed for clean up.
    * Codebook.docx is a R markdown Knitted Word document. It provides the same information.
  * run_analysis.R performs the data preparation and 5-steps for generating a Tidy data file, as described in the course project’s definition: 
    * Merges the training and the test sets to create one data set.
    *	Extracts only the measurements on the mean and standard deviation for each measurement.
    *	Uses descriptive activity names to name the activities in the data set
    *	Appropriately labels the data set with descriptive variable names.
    *	From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
  * FinalData.txt is the exported final data after going through all the sequences described above.
  * Raw R code that generates FinalData.txt
  * R markdown code for generating both Codebooks .md and .docx

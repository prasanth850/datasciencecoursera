Getting and Cleaning Data Course Project
# Criteria
1. The submitted data set is tidy.
2. he Github repo contains the required scripts.
3. GitHub contains a code book that modifies and updates the available codebooks with the data to indicate all the variables and summaries calculated, along with units, and any other relevant information.
4. The README that explains the analysis files is clear and understandable.
5. The work submitted for this project is the work of the student who submitted it.
# Given Instructions
The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. 
The goal is to prepare tidy data that can be used for later analysis. 
You will be graded by your peers on a series of yes/no questions related to the project. 
You will be required to submit: 
1) A tidy data set as described below
2) A link to a Github repository with your script for performing the analysis
3) A code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md.
4) You should also include a README.md in the repo with your scripts. This repo explains how all of the scripts work and how they are connected.

One of the most exciting areas in all of data science right now is wearable computing - see for example this article. 
Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. 
The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. 
A full description is available at the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Here are the data for the project:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

#Input Dataset
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
run_analysis.R: this script takes the input data, and creates the output file
# Analysis
The script first downloads and unzips the dataset from the above url. 
(1) The script then reads the test and training sets, merges them . 
(2) It filters down the mean and std features, and selects only these 
(3) It merges in the activity names for the activities 
(4) It then builds up a series of labeled columns to represent single variables from the feature. 
(5) It calculates the average of each variable and writes out this data set to tidy_data.txt 
# Output
final dataset: "tidy_data.txt"
# Codebook
CodeBook.md: describes the variables, the data, and any transformations or work that you performed to clean up the data

# CodeBook for Peer-graded Assignment Week 4: Getting and Cleaning Data Course Project

This codebook explains the `run_analysis.R` script, which performs the data download preparation and then followed by the 5 steps: 

1. **Download the dataset**
    + Dataset downloaded and extracted under the folder called `UCI HAR Dataset`
    
    <br/>
2. **Assign each data to variables**
    
3. **Merges the training and the test sets to create one data set**
   
4. **Extracts only the measurements on the mean and standard deviation for each measurement**
    
5. **Uses descriptive activity names to name the activities in the data set**
    
6. **Appropriately labels the data set with descriptive variable names**
   
7. **From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject**
    + `FinalData` (180 rows, 88 columns) is created by sumarizing `TidyData` taking the means of each variable for each activity and each subject, after groupped by subject and activity.
    + Export `FinalData` into `FinalData.txt` file.
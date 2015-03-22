## Course Project

### Process

The script run_analysis.R does the following in order to clean up the data and produce tidy data sets:

1. Merges all sets to create one data set.

2. Reads features.txt and uses only the measurements on the mean and standard
   deviation for each measurement. 

3. Reads activity_labels.txt and uses the name function to rename the activities.

4. Reformats names to make them more user-friendly.

5. Merges the features with activity labels and subject IDs. The result is
   saved as tidyData.txt.

6. The average of each measurement for each activity and each subject is merged
   to form a second data set, which is then saved (tidyData2.txt).


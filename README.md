# run_analysis.r
Course project for Getting and Cleaning Data

The 'run_analysis.R' script assumes that you have the unzipped UCI HAR Dataset in a folder in your workking directory (if you don't have the data, uncomment the first section of the script and it will download it for you). The script then does the following:
* 1) Loads necessary library, and downloads and unzips the data file (uncomment these lines if necessary)
* 2) Merges the training and the test sets to create one data set by creating three functions (make_subject_dataset, make_X_dataset, make_y_dataset), and running these functions.
* 3) Extracts only the measurements on the mean and standard deviation for each measurement (by creating and running a function named get_selected_measurements).
* 4) Uses descriptive activity names to label the activities in the data set
* 5) Appropriately labels the data set with descriptive activity names. 
* 6) Creates an intermediate dataset with all required measurements.
* 7) Creates the final, independent tidy data set with the mean and standard deviation of each variable for each activity and each subject.

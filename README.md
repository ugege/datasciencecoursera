# Explanations on how the script run_analysis.R works
1.	Load required packages (bitops and RCurL)
2.	Check if UCI HAR Dataset exist in your working directory if not create it and download the required data
3.	Unzip the downloaded data into the directory created
4.	Merge the training and test dataset to create one data set
5.	Extract only measurement with mean and standard deviation from each measurement
6.	Use descriptive activity names to name the activities 
7.	Label the dataset with descriptive activity names and save the first dataset into the text file merged_dataset.txt
8.	Create a second independent tidy data and save into the text file average_dataset.txt

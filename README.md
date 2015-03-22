# Cleaning_Data
homework for data scientist class

The script run_analysis.R needs to have the data loaded from 
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 
before it will function correctly.

Refer to the CodeBook for instructions.

Output file is a text file containing subject and activity with measurement averages.
     Column V1 shows the subjects
     Column V2 shows the activity
     Column V3 shows the average of the measurements

There are two environmental variables that are created -- Measurement_Means and Measurement_Std_Dev.  These variables are created by the run_analysis.R script.  The Measurement_Means calculates the mean for all of the various measurements.  The Measurement_Std_Dev calculates the standard deviation for the various meansurements.

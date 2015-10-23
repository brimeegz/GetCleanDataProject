The Variables:
There are 68 variables in total
Subject: ID ranging from 1 to 30 for each participant
Activity: ranging from 1 to 6 corresponding with walking, walking upstairs, walking downstairs, sitting, standing, and laying (respectively)
The remaining 66 variables consist of 33 mean and 33 standard deviation values.
The prefix t denotes time domain values whereas f denotes frequency domain values.

The Data:
The original data was collected from accelerometers from a smartphone from 30 participants over time.

Transformations of the data:
The data was transformed as follows
- only means and standard deviations were kept
- the variable names were modified for ease of reading
- the test data tables were combined (activity code + participant ID + measurements)
- similarly, the training data tables were combined
- the combined test and training data frames were combined
- a a table consisting of the average of each variable across each participant and each activity was calculated
- this table was converted to long format for ease of reading
- the table was saved as "finalTable.txt"




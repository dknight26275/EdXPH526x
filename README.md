# EdXPH526x
Final assignment for EdxPH526x Python for Research online course

**Introduction**
In this final project for EdXPH526x, we attempt to predict the type of physical activity (e.g., walking, climbing stairs) from tri-axial smartphone accelerometer data. Smartphone accelerometers are very precise, and different physical activities give rise to different patterns of acceleration.

**Input Data**
The input data used for training in this project consists of two files. The first file, train_time_series.csv, contains the raw accelerometer data, which has been collected using the Beiwe research platform, and it has the following format:

timestamp, UTC time, accuracy, x, y, z

The timestamp column is used as the time variable while colummns x, y, and z correspond to measurements of linear acceleration along each of the three orthogonal axes.
The second file, train_labels.csv, contains the activity labels. Different activities have been numbered with integers. We use the following encoding: 1 = standing, 2 = walking, 3 = stairs down, 4 = stairs up. Because the accelerometers are sampled at high frequency, the labels in train_labels.csv are only provided for every 10th observation in train_time_series.csv.

**Activity Classification**
The goal is to classify different physical activities as accurately as possible. To test the code, we're also provided a file called test_time_series.csv, and at the end of the project we're asked to provide the activity labels predicted by the code for this test data set. Only the course staff have the corresponding true labels for the test data, and the accuracy of your code will be determined as the percentage of correct classifications. 

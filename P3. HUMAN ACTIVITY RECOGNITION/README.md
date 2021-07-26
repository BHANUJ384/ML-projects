HumanActivityRecognition

This project is to build a model that predicts the human activities such as Walking, Walking_Upstairs, Walking_Downstairs, Sitting, Standing or Laying.

This dataset is collected from 30 persons(referred as subjects in this dataset), performing different activities with a smartphone to their waists. The data is recorded with the help of sensors (accelerometer and Gyroscope) in that smartphone. This experiment was video recorded to label the data manually.


By using the sensors(Gyroscope and accelerometer) in a smartphone, they have captured '3-axial linear acceleration'(_tAcc-XYZ_) from accelerometer and '3-axial angular velocity' (_tGyro-XYZ_) from Gyroscope with several variations. 

In the dataset, Y_labels are represented as numbers from 1 to 6 as their identifiers.

 WALKING as __1
 WALKING_UPSTAIRS as __2
 WALKING_DOWNSTAIRS as __3
 SITTING as __4
 STANDING as __5
 LAYING as __6
    
 Readings are divided into a window of 2.56 seconds with 50% overlapping. 

* Accelerometer readings are divided into gravity acceleration and body acceleration readings,
  which has x,y and z components each.

* Gyroscope readings are the measure of angular velocities which has x,y and z components.

* Jerk signals are calculated for BodyAcceleration readings.

* Fourier Transforms are made on the above time readings to obtain frequency readings.

* Now, on all the base signal readings., mean, max, mad, sma, arcoefficient, engerybands,entropy etc., are calculated for each window.

* We get a feature vector of 561 features and these features are given in the dataset.

* Each window of readings is a datapoint of 561 features.

 All the data is present in 'UCI_HAR_dataset/' folder in present working directory.
     - Feature names are present in 'UCI_HAR_dataset/features.txt'
  
  Train Data___
      -'UCI_HAR_dataset/train/X_train.txt'
      - 'UCI_HAR_dataset/train/subject_train.txt'
      - 'UCI_HAR_dataset/train/y_train.txt'
  Test Data___
      - 'UCI_HAR_dataset/test/X_test.txt'
      - 'UCI_HAR_dataset/test/subject_test.txt'
      - 'UCI_HAR_dataset/test/y_test.txt'
 


data source- https://archive.ics.uci.edu/ml/machine-learning-databases/00240/




# Human-Activity-Recognition-using-ML
The data contain readings of the sensor in a smartphone which is attached to the volunteer. The task is to identify the activity the volunteer is performing .
1. Title: Smartphone Dataset for Human Activity Recognition 

2. Relevant Information:
   -- This dataset has been derived from 
      https://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
      
      The dataset was collected from the in-built accelerometer and gyroscope of a 
      smartphone worn around the waist of participants.
      The data was collected from 30 participants within the age group of 22-79 years. 
      Each activity (standing, sitting, laying, walking, walking upstairs, walking downstairs) was 
      performed for 60secs and the 3-axial linear acceleration and 3-axial angular velocity  were 
      collected at a constant rate of 50Hz.
   
 
2.-Results: We obtained an overall accuracy of 95.82 with Logistic Regression,
                  95.04% for SVM and 92.22% for Randome Forest.
                  

3. Number of Instances: 5744 

5. Number of Attributes: 561 (See features.txt and features_info.txt included, taken from 
   https://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones) 

6. Attribute Information:
   For each record in the dataset it is provided: 
   - Triaxial acceleration from the accelerometer (total acceleration). 
   - Triaxial Angular velocity from the gyroscope. 
   - A 561-feature vector with time and frequency domain variables 

**Case Study 1: Supervised Learning**

Objectives

To explore classical machine learning for supervised classification
To apply code in implementing a machine learning model for both classification and regression problem
To analyze results and assess quality of models

**Regression Problem**

1. Download the file AirQualityUCI.csv from Canvas and examine the following features:
   CO(GT)
   NMHC(GT)
   C6H6(GT)
   NOx(GT)
   
3. Write code that converts the dataset into corresponding x and y values for regression. Take note of the following:
   How big is your window for x?
   Will you consider just one dimension for y or multiple?
   
4. Partition your x and y datasets for each of the features in #1 by using a ratio of 80% for training and 20% for testing. Choose a model from sklearn and train it for prediction. Measure it's performance. Take note that there are 4 features (i.e. 4 sequences). This means you would need 4 models to train and get its performance.

4. Answer the following guide questions:
   a) Does changing the window size x affect the performance? Try out different sizes and see for yourself. Why is this the case based on how long or how short the window size is?
   b) If you were to assess the air quality based on those 4 features, how would you say that your model is "acceptable" in terms of predicting air quality?

**Classification Problem**

1. Download the file rice.csv and convert the label classes to 1 and 0

2. Partition the dataset to 80% training and 20% testing.

3. Choose a model in SKLearn and train against the 80% and measure its accuracy in the 20%.

4. Repeat the process again but this time using 70% training and 30% testing, 60% training and 40% testing and finally 50% training and 50% testing. Make sure each partitioning scheme is randomly sampled.

5. Answer the following guide questions:
   a) Is there a trend that you notice as the training size goes smaller and the testing size gets bigger? (show proof if there is)
   b) If ever there is a trend, will this be a valid measure of performance of a model? Why or why not?

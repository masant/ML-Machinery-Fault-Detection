# ML-Machinery-Fault-Detection
Final project for MBA in Data Science &amp; Analytics - USP/Esalq

This repository has been created aiming to share the developed code for my final project in MBA in Data Science &amp; Analytics - USP/Esalq.


## Fault Diagnosis in Rotating Machines using vibration signals and classification algorithms.

This study conducts a comparative analysis of three classification models applied to the diagnosis of faults in rotating machinery. The research utilizes the MaFaulDa dataset, consisting of sensor data collected from a rotating machine under simulated common fault scenarios. From the raw data, features were extracted in the frequency domain using the Fast Fourier Transform, and additional statistical features were derived from the time-domain data, including kurtosis, entropy, and mean. With the extracted features, a comparative analysis was performed on the following classification models: Random Forest, Support Vector Machines (SVM), and Gradient Boosting. The primary objective was to evaluate the effectiveness of these models in detecting fault scenarios in rotating machinery through an initial performance comparison of these three approaches.


## Repository notes

* I divided this project in two parts: 
  * Feature extraction: You can verify this project section in the file FeatureExtractioncsv.ipynb. Basically, I get the raw data from a .zip file available in MaFaulda dataset, convert this data to frequency domain using FFT and got the frequency features. In addition, I also some time domain features to be used in the models.
  * Machine learning models: I compared three machine learning models in my project: Random Forest, SVM and Gradient Boosting.



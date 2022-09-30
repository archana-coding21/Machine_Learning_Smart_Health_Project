# Machine_Learning_Smart_Health_Project
Week1_Project1_Files
This is part of the first assignment Project 1 for the Machine Learning for Smart Health Systems Course by Omdena.

The information about all the records available on the Physionet for the Apnea-ecg database have been downloaded and initianl analysis has been performed using various plots and graphs for both the Healthy people and the Patients with Apnea.

The python code for the same is provided in the https://github.com/archana-nallam/Machine_Learning_Smart_Health_Project/blob/main/Apnea_Physionet_dataset_.ipynb

Next, the individual records have been downloaded from the Physionet database for performing HRV Analysis. The HRV Analysis application has been used for this purpose but it coudd not function properly. Kubios HRV also did not accept all the file formats and hence the feature extraction has been performed using the python code.

The code used for the feature extraction is in this link: 
https://github.com/archana-nallam/Machine_Learning_Smart_Health_Project/blob/main/project%201/Apnea_ECG_Database_Feature_extraction.ipynb

Further Analysis was done on the extracted features list provided in an excel format. Python code has been used for the same and various plots have been plotted to understand the distribution of each feature among the Patients and the Healthy people. Based on the distribution of each feature, the Inferential Statistics has been performed using the T-Test and the Mann Whitney U test on those features.

This Analtysis is provided in the link: 
https://github.com/archana-nallam/Machine_Learning_Smart_Health_Project/blob/main/Statistical_Analysis_on_Extracted_Features.ipynb

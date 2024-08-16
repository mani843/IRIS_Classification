# IRIS_Classification
End-to-end ML pipeline
This code is for a building an end-to-end ML pipeline. 
An IRIS plant classification problem has been chosen for this assignment. 
This is an elementary dataset. 
IRIS_Data_Cleaning.py : Data set is loaded and analysed.  Any missing and null values are evaluated. Further the data set is normalized and the class feature is encoded. The cleaned dataset is saved in google drive.

IRIS_Model_Building.py : cleaned data set is loaded in the file. Data is split in train and test dataset. Random Forest Classifier model is trained. The model is saved in google drive and then loaded from google drive. (I couldnot do this step in separate file)

IRIS_api.py : api for use of trained model is created.

IRIS_app.py : application for use of model is created. ( I am getting error in output)

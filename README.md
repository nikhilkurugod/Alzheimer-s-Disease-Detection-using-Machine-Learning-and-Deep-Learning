# Alzheimer's Disease Detection using Machine-Learning and Deep-Learning

![image](https://github.com/user-attachments/assets/68da73a9-6b20-42db-8b05-943fabae03a5)

# The above diagram represents System Overview.

 Machine learning models use the kaggleDataset1 and kaggleDataset2 datasets for training and it is tested for performance evaluation. Two machine learning models are used, the first ML model uses HOG for feature 
 selection and then uses SVM classifier for classification. The second model uses K-Nearest Neighbor (KNN) and RF for classification.

# Datasets used have four different classes they are :
Non Demented,
Very Mild Demented,
Mild Demented,
Moderate Demented,

![image](https://github.com/user-attachments/assets/7bcfa828-b2d1-4333-b724-7862fdf672b2)

Brain MRI indicating severity of AD. Top row images from left: a) Mild Demented, b) Moderate demented. Bottom row from left c) Very Mild Demented, d) Non Demented

# Results for Two ML models tested for two different kaggledatasets

![image](https://github.com/user-attachments/assets/aa028d42-7a3c-4576-9f07-0d25d09b5b54)


Alzheimer's Disease detection using deep learning models such as DenseNet169 and MobileNetV2

Brain MRI contains information about the brains state and behaviour, by using this we can easily detect the severity of Alzheimer's disease (AD). Using deep learning (DL) we can create a model that can classify the brain MRI as per the severity. The dataset used in this project is from OASIS.

The image gives the brain MRI from each class. From the image it can be seen that the ventricles of brain start to increase in size as the severity of AD increases. For DL model MobileNetV2 architecture is used for training and testing of the dataset. OASIS dataset is used for training and testing. The python notebook in this repo has the results along with the code. For testing the code, download all the files and change the directory of dataset with the path of the directory of the dataset where it is downloaded for train, validate and test dataset. Other MRI scans also be tested by changing the directory of test dataset in the code. Adam optimizer is used in this code wih learning rate of 0.0001 .The parameters can be changed to and tested accordinng to the requirements.

# Results for DL Models

![image](https://github.com/user-attachments/assets/2caec085-7f5d-40ad-9e89-c4955a898d2d)


# Alzheimer's Disease Detection using Machine-Learning and Deep-Learning
Alzheimer's Disease detection using deep learning models such as DenseNet169 and MobileNetV2

Brain MRI contains information about the brains state and behaviour, by using this we can easily detect the severity of Alzheimer's disease (AD). Using deep learning (DL) we can create a model that can classify the brain MRI as per the severity. The dataset used in this project is from OASIS.

# Datasets used in this code have four classes they are :
Non Demented
Very Mild Demented
Mild Demented
Moderate Demented

![image](https://github.com/user-attachments/assets/7bcfa828-b2d1-4333-b724-7862fdf672b2)

Brain MRI indicating severity of AD. Top row images from left: a)Mild Demented, b)Moderate demented. Bottom row from left c)Very Mild Demented, d)Non Demented

The image gives the brain MRI from each class. From the image it can be seen that the ventricles of brain start to increase in size as the severity of AD increases. For DL model MobileNetV2 architecture is used for training and testing of the dataset. OASIS dataset is used for training and testing. The python notebook in this repo has the results along with the code. For testing the code, download all the files and change the directory of dataset with the path of the directory of the dataset where it is downloaded for train, validate and test dataset. Other MRI scans also be tested by changing the directory of test dataset in the code. Adam optimizer is used in this code wih learning rate of 0.0001 .The parameters can be changed to and tested accordinng to the requirements.

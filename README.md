# Automated-Diagnosis-of-Pneumonia-in-Chest-X-rays


## Background:

Pneumonia is a prevalent disease that can be classified into different types: bacterial pneumonia, viral pneumonia, mycoplasma pneumonia, and fungal pneumonia. However, the dataset used for this task contains samples only from the first two classes. Additionally, the dataset is small and imbalanced, posing a challenge for developing an effective deep learning model. Despite deep learning models typically requiring large amounts of data, it is still possible to construct robust models with limited data by understanding the underlying principles and techniques. The goal here is to explore and create deep learning models for pneumonia detection using the available dataset.

![](https://www.scientificanimations.com/wp-content/uploads/2018/06/Pathogens-causing-pneumonia_180607_04.jpg)


## Dataset

### [Pneumonia CRX images](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)

The dataset is organised into 3 folders (train, test, val) and contains 5,863 X-Ray images.

The data was made into 2 form:

  - Binary Classes (Normal, Pneumonia)
  - Multi Classes (Normal, **Pneumonia was sub-divided into Bacterial and Viral Pneumonia.**)

**Data Cleaned, Augmented to `mitigate class imbalance`**


![](https://github.com/Lawrytime/Automated-Diagnosis-of-Pneumonia-in-Chest-X-rays/blob/main/Data%20Distribution%20(Post-Augmenttation)%20.png)

## Image Processing Point of View

![](https://github.com/Lawrytime/Automated-Diagnosis-of-Pneumonia-in-Chest-X-rays/blob/main/assets/img_process.png)

##  

# Model Architectures

## Basic CNN Model Implemented:

![](https://github.com/Lawrytime/Automated-Diagnosis-of-Pneumonia-in-Chest-X-rays/blob/main/assets/CNN.png)

##  

## Receptive Fields

![](https://github.com/Lawrytime/Automated-Diagnosis-of-Pneumonia-in-Chest-X-rays/blob/main/assets/RF.png)

##  

## Transfer Learning:

### Model Architecture implementation was carried out for 3 pre-trained Models:

### AlexNet Architecture Implemented


![](https://github.com/Lawrytime/Automated-Diagnosis-of-Pneumonia-in-Chest-X-rays/blob/main/assets/alexnet.png)


## Receptive Fields

![](https://github.com/Lawrytime/Automated-Diagnosis-of-Pneumonia-in-Chest-X-rays/blob/main/assets/RF_Alex.png)

### GoogLeNet
...

### ResNet
...

### 

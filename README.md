# **Food Image Classification**

### **Objective:**
The main objective of the project is to build a Multi-Class Image Classifier to identify the food category, given an image of food.

### **Dataset:**
The Dataset "Food-11 image dataset" is obtained from Kaggle (click [here](https://www.kaggle.com/trolukovich/food11-image-dataset)). 
This dataset contains 16643 food images grouped in 11 major food categories. There are 3 splits in this dataset:
* Training
* Validation
* Evaluation

### **Architecture Used:**
The following Neural Network Architechture are used to build models using Transfer Learning in Python:
* Inception V3 
* VGG 16       


### **Evaluation:**
The Metric used for evaluation is **Accuracy**.

### **Outcome:**
The models obtained the following accuracy after fine tuning them
| Model | Accuracy |
| ------ | ------ |
| VGG-16 | 86.13% |
| Inception V3 | 91.88% |

Inception V3 was selected as the finalized model.

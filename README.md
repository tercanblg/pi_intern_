
# Pear Inc. Smart T-Shirt Antivirus

Welcome to Pear Inc.! This repository contains the proof-of-concept code for a lightweight antivirus system designed to approve apps for our new line of smart t-shirts. The smart t-shirts will use Google Wear OS, allowing users to install custom programs through the Google Play Store. The antivirus ensures that only Pear Inc. approved programs can be installed to prevent ransomware and other malicious software from compromising our premium smart t-shirts.

## Project Overview

This project involves:
- Loading and visualizing the dataset.
- Cleaning the dataset (handling missing values and balancing the classes).
- Creating a simple model to classify app signatures as 'Virus' or 'Not a Virus'.
- Evaluating the model and visualizing the results.
- Uploading the code to a private GitHub repository and inviting collaborators.

## Dataset

The dataset is a CSV file with the following structure:
- Four feature columns representing the dimensions of the numerical signatures.
- A label column (`isVirus`) indicating whether the app is a virus (True) or not (False).
- You can install the required libraries using the following command:


## Requirements

- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn


### Don't  forget download this library 

```
pip install pandas matplotlib seaborn scikit-learn
```

# Steps
## 1. Load and Visualize the Data
Load the dataset and visualize it to understand the distribution of features and the balance of labels.

### Distribution of Each Feature
This helps to visualize the relationships between features and how they separate the virus and non-virus instances


![6518e890-35c9-4668-b896-584694fff4c2](https://github.com/tercanblg/pi_intern_questions/assets/141034053/1a135080-ce08-44d4-b099-e9ea1695ccda)

## Count of Each Class
bar plot showing the count of virus and non-virus instances in the dataset. This helps to visualize the class imbalance
![ec02ecfb-b46b-4b1b-9fd4-ec362a1a703e](https://github.com/tercanblg/pi_intern_questions/assets/141034053/a638a35d-2998-41fa-8b08-7683404ee760)
b

## 2. Clean the Data
Handle missing values and balance the dataset.
### pair plot of the balanced data


![968e28e4-67e4-4373-8c69-a878edd554f5](https://github.com/tercanblg/pi_intern_questions/assets/141034053/e7251804-82a9-42db-9e8b-a807b98cc9a7)

### count plot
count plot to visualize the distribution of the isVirus label in the balanced dataset

![809494cf-37c4-4fd1-9b19-6bc5df614461](https://github.com/tercanblg/pi_intern_questions/assets/141034053/0a33b10c-5fdd-43f4-95f6-b5f3605c34a8)



## 3. Create a Simple Model
Train a simple model (e.g., logistic regression) to classify the signatures.

### the confusion matrix

![07b95880-9a68-4864-8437-756ce23d8b96](https://github.com/tercanblg/pi_intern_questions/assets/141034053/1ef6597b-0cb5-436c-911e-22211dfed3f1)

### Plot ROC curve
![5726d2ce-298a-484d-8bc5-feb35c789e82](https://github.com/tercanblg/pi_intern_questions/assets/141034053/756cb601-4b6d-4bb1-ada7-ac68fa3d7d64)

![07b95880-9a68-4864-8437-756ce23d8b96](https://github.com/tercanblg/pi_intern_questions/assets/141034053/f69ce416-d427-4362-a624-dd80e23cefb6)
### I have created a proof-of-concept antivirus system for Pear Inc.'s smart t-shirts. The model can classify app signatures as 'Virus' or 'Not a Virus', helping to protect users from malicious software.



# Disease Prediction using Machine Learning

## Introduction
With the evolving landscape of health information seeking behavior globally, there's a growing demand for online resources that provide insights into diseases, diagnoses, and treatments. Creating a recommendation system tailored for medical professionals and patients alike, utilizing review mining, can significantly save time and improve decision-making processes. However, understanding the vast and often complex medical vocabulary poses a challenge for users, particularly laymen. Hence, there's a need for a system that adapts to the unique requirements of the health domain users.

## Files Overview

### `training.csv`
- This dataset serves as the primary data source for the project. It contains two main columns: "Disease" and "Symptoms". The dataset has been preprocessed to facilitate easy classification and is utilized for training the machine learning model.

### `testing.csv`
- This dataset is used to evaluate the model's performance, enabling the assessment of its accuracy. It comes pre-defined with expected outputs.

### `Compiled_Report.pdf`
- This document provides a comprehensive explanation of each module implemented in the software. For detailed insights into every aspect of the project, refer to this PDF.

### `PythonCodeOfAlgorithm.py`
- This file contains the code implementing various algorithms used for training the model, including:
  - Decision Tree
  - Random Forest
  - KNearestNeighbour
  - Naive Bayes
  These algorithms collectively achieve an accuracy rate exceeding 90%.

### Database
- The project utilizes an SQLite database named `database.db`, comprising four tables showcasing the results of four different algorithms. User results are stored along with their names for future preferences.

![](https://github.com/Lovely-Professional-University-CSE/int247-machine-learning-project-2020-kem031-sudhanshu/blob/master/Database/db1.jpeg)

### `GUI.py`
- This file is responsible for creating the graphical user interface (GUI) of the system. Utilizing Tkinter, it provides a user-friendly interface where users can input disease symptoms and receive disease predictions through various algorithms.

### `Project_ML.ipynb`
- This Jupyter notebook contains the complete code of the project. It serves as a detailed guide explaining the functionality of each module utilized in the project.

### `GUI.jpeg`
- This image depicts a screenshot of the GUI built for the system, showcasing its functionality and design.

## Using the GUI

### Step 1:
Enter the patient's name in the provided space labeled as "Name of the Patient". This is a mandatory field required for obtaining results.

### Step 2:
Select five symptoms from the dropdown menu labeled as Symptom 1 to Symptom 5. If the user is unsure of five symptoms, they must enter at least two initial symptoms. Failure to do so will result in a prompt indicating missing information.

### Step 3:
Based on user preference, disease prediction can be made using different algorithms such as Decision Tree, Random Forest, Naive Bayes, and K-Nearest Neighbor. Click on the corresponding buttons:
- Press Prediction 1 for Decision Tree algorithm
- Press Prediction 2 for Random Forest algorithm
- Press Prediction 3 for Naive Bayes algorithm
- Press Prediction 4 for K-Nearest Neighbor algorithm
(Users can predict the disease using more than one algorithm simultaneously)

### Step 4:
The predicted disease will be displayed in front of the labels of the selected algorithm(s).

### Step 5:
Click on the "Reset" button to predict the disease for another patient or press the "Exit System" button to close the GUI.

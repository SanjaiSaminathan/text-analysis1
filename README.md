# text-analysis1

README.md for CE807-24-SP Assignment
This repository contains the code for CE807-24-SP Assignment. The code is organized into three main sections:

Common Codes: This section contains common functions and utilities used across different models.
Method Generative: This section implements the first method, a Generative Model, for text classification.
Method Discriminative: This section implements the second method, a Discriminative Model, for text classification.
Other Method/model: This section contains additional methods or models for text classification, if any.
Requirements
Before running the code, make sure you have the following libraries installed:

bash

Open In Editor
Edit
Run
Copy code
!pip install transformers
!pip install datasets
!pip install -U imbalanced-learn
!pip install --upgrade scikit-learn
!pip install --upgrade imbalanced-learn
!pip install tensorflow
!pip install joblib
!pip install -U -q PyDrive
File Structure
The repository follows the following file structure:


Open In Editor
Edit
Copy code
student_id
  |
  ├── data
  │   └── number
  │       ├── train.csv
  │       ├── valid.csv
  │       └── test.csv
  │
  ├── model
  │   ├── number
  │   │   ├── Model_Gen
  │   │   │   └── model.sav
  │   │   └── Model_Dis
  │   │       └── model.sav
  │   └── Model_Gen.zip
  │   └── Model_Dis.zip
  └── code.ipynb
student_id: This folder contains all the code and data related to your specific student ID.
data: This folder contains the training, validation, and test data for the assignment.
model: This folder contains the trained models for both the Generative and Discriminative methods.
code.ipynb: This Jupyter notebook contains the code for the assignment, including the common code, the Generative and Discriminative models, and the main function to run the code.
Instructions
Replace student_id with your actual student ID.
Download the data and model folders from the provided Google Drive link.
Mount your Google Drive in Colab.
Run the code in the code.ipynb notebook.
Running the Code
The code is organized into a series of functions that can be run interactively from the code.ipynb notebook. The main function provides a simple menu to select the desired action:


Open In Editor
Edit
Copy code
0. To Exit Code
1. Train Model Generative
2. Test Model Generative
3. Train Model Discriminative
4. Test Model Discriminative
Enter your option:
You can select the desired action by entering the corresponding number and pressing enter.

Output
The code will produce the following outputs:

Training and validation performance metrics: The code will print the training and validation performance metrics for both the Generative and Discriminative models, including accuracy, precision, recall, and F1 score.
Confusion Matrix: The code will display the confusion matrix for both models, showing the number of true positives, true negatives, false positives, and false negatives.
Model files: The trained models will be saved as .sav files in the model folder.
Output CSV files: The code will generate output CSV files containing the predicted labels for the test data. These files will be saved in the data folder.
Notes
The code uses a seed based on your student ID to ensure reproducibility of results.
The code uses Google Drive to store the data and models.
The code follows standard Python coding and documentation practices.
You are encouraged to explore the code and modify it to improve the performance of the models.

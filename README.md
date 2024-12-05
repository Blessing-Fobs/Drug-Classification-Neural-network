# Drug-Classification-Neural-network
Short Description
This project implements a neural network model to classify drugs based on patient information. Using features such as age, sex, blood pressure (BP), cholesterol, and sodium-to-potassium ratio (Na_to_K), the model predicts the most suitable drug class. The project achieves high accuracy and provides evaluation metrics like confusion matrix and classification reports.

#Getting Started
The following instructions will help you set up the project on your local machine.

#Prerequisites
To run this project, ensure you have the following installed on your system:
Python 3.7+
Pip (Python package manager)
Jupyter Notebook (optional for notebook execution)
Python libraries
Numpy
pandas
scikit-learn
matplotlib

#Installing
Clone the respository:
git clone https://github.com/yourusername/drug-classification.git
cd drug-classification
Install the required dependencies
pip install -r requirements.txt
Dataset:
Ensure the drugdataset.csv file is available in the project directory. This file contains the patient data used for training and testing.
Age, Sex, BP, Cholesterol, Na_to_K, Drug
23, 1, 2, 1, 25.355, drugY
47, 0, 1, 1, 13.093, drugC
...

#Running the Tests
Running all tests:
Tests are included to ensure the accuracy of preprocessing, training, and evaluation steps. Run all tests with:
pytest tests/
Tests Breakdown:
Data Preprocessing Tests: 
Validate the scaling and transformations applied to the dataset to ensure consistency.
Model Training Tests
Check that the neural network model trains correctly and meets baseline performance metrics.
Prediction Tests
Ensure the model provides accurate predictions on the test set and handles edge cases appropriately.

#Deployment
Deploment Steps:
Train the model using the main.py script:
python main.py
Save the trained model to the models/ directory for reuse. The current implementation handles this step automatically.
Integrate the trained model into an API, web application, or command-line tool for real-world use.

#Contributing:
We welcome contributions!
Please read the CONTRIBUTING.md file for our code of conduct and submission process.

#Versioning:
We use SemVer for versioning. For available versions, see the tags on this repository.

#Author:
Mbonghe Blessing
GitHub: Blessing-Fobs
Email: bmbonghe17@gmail.com

#License:
This project is licensed under the MIT License. See the LICENSE file for more details.

#Acknowledgement:
This project is made possible by the following:
Scikit-learn Documentation: For providing extensive guidance on using machine learning models.
Pandas and NumPy Teams: For their invaluable data manipulation and numerical computing tools.
Matplotlib: For enabling easy visualization of model outputs.
Machine Learning Communities: For sharing insights, tutorials, and best practices.



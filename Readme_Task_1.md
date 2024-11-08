# Movie Genre Classification

This repository contains a project focused on **Movie Genre Classification** using text-based data. The project involves training a model to predict movie genres based on movie titles and descriptions. The dataset used includes training, testing, and solution files.

## Project Overview

The goal of this project is to classify movies into their respective genres using text data. We leverage machine learning techniques to build a classification model that can predict genres based on movie titles and descriptions.

## Dataset

The dataset consists of three main files:
- **train_data.txt**: Contains training data with columns for `Title`, `Genre`, and `Description`.
- **test_data.txt**: Contains test data with columns for `Id`, `Title`, and `Description`.
- **test_data_solution.txt**: Contains the solution for the test data with columns for `Id`, `Title`, `Genre`, and `Description`.

The data is read using the `pandas` library, with a custom separator (`:::`).

## File Structure

```bash
├── Task 1 MovieGenre.ipynb          # Jupyter Notebook with the project code
├── Genre Classification Dataset/
│   ├── train_data.txt               # Training dataset
│   ├── test_data.txt                # Testing dataset
│   └── test_data_solution.txt       # Solution for the test dataset
└── README.md                        # Project documentation
## Requirements

To run this project, you need to have the following dependencies installed:

- Python 3.x
- pandas
- numpy

You can install these dependencies using:

```bash
pip install pandas numpy
 ## Project Workflow

The project workflow involves the following steps:

1. **Data Loading**: Load the training and testing datasets.
2. **Data Preprocessing**: Clean and preprocess the text data for analysis.
3. **Exploratory Data Analysis (EDA)**: Analyze the distribution of genres, word frequencies, etc.
4. **Feature Engineering**: Convert text data into numerical features using techniques like TF-IDF or Count Vectorizer.
5. **Model Training**: Train machine learning models such as Naive Bayes, Logistic Regression, or SVM for genre classification.
6. **Model Evaluation**: Evaluate the model's performance using metrics like accuracy, precision, recall, and F1-score.
7. **Prediction**: Predict genres for the test dataset and compare with the ground truth.

Usage
To run the notebook, use the following command in your terminal:

bash
Copy code
jupyter notebook "Task 1 MovieGenre.ipynb"
Make sure to place the dataset files in the correct directory as specified.

Results
After training and evaluating the model, you can expect results showing the classification accuracy, confusion matrix, and other performance metrics. The final predictions can be compared with the provided solution file.

Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to create a pull request.

License
This project is open-source and available under the MIT License.

Contact
For any questions or issues, please reach out to:

Nandkishor Gupta
Email: nandkishorgupta544@gmail.com 

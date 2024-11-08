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

# Naive Bayes Classifier Project

This project demonstrates the usage of Naive Bayes classifiers (BernoulliNB and GaussianNB) on a sample dataset. The dataset is loaded, preprocessed, and then used to train and evaluate the classifiers.

## Table of Contents

- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Dataset

The dataset used in this project is stored in a CSV file named `naivebayes.csv`. It consists of two feature columns and one target column.

## Installation

To run this project, you'll need to have Python installed along with the following libraries:

- numpy
- pandas
- scikit-learn
- matplotlib

You can install the required libraries using pip:

```bash
pip install numpy pandas scikit-learn matplotlib
```
## Usage

Clone the repository or download the project files.

Ensure that the dataset file (naivebayes.csv) is in the same directory as the script.

Run the script:

```bash
python naive_bayes_classifier.py
```
The script will load the dataset, split it into training and testing sets, standardize the features, and train two Naive Bayes classifiers (BernoulliNB and GaussianNB). It will then make predictions on the test set and display the confusion matrices and accuracy scores for both classifiers.


## Results

The script will output the following:

- Predictions made by the BernoulliNB and GaussianNB classifiers on the test set.
- Confusion matrices for both classifiers.
- Accuracy scores for both classifiers.

Example output:

```lua
BernoulliNB Predictions: [0 1 1 0 ...]
Confusion Matrix for BernoulliNB:
[[13  3]
 [ 2 12]]
Accuracy for BernoulliNB: 0.8333

GaussianNB Predictions: [0 1 1 0 ...]
Confusion Matrix for GaussianNB:
[[14  2]
 [ 3 11]]
Accuracy for GaussianNB: 0.8333

```

This file provides a comprehensive overview of the project, including how to set it up and run it, as well as what to expect from the output.

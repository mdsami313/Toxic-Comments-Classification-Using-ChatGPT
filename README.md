# Multi-Headed Toxicity Detection Model

![Toxicity Detection](https://img.shields.io/badge/toxicity-detection-blue.svg)
![Status](https://img.shields.io/badge/status-active-brightgreen.svg)
![License](https://img.shields.io/badge/license-MIT-orange.svg)

## Introduction

Welcome to the Multi-Headed Toxicity Detection Model project! This repository contains a state-of-the-art multi-headed neural network designed to detect various types of toxicity in online comments, such as threats, obscenity, insults, and identity-based hate. This project aims to improve the quality of online discussions by identifying and managing toxic comments effectively.

## Table of Contents

- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Model Architecture](#model-architecture)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Overview

This project involves:

1. **Data Preparation**: Loading, cleaning, and preprocessing text data.
2. **Exploratory Data Analysis (EDA)**: Understanding data distribution, visualizing relationships, and uncovering insights.
3. **Model Building**: Creating a multi-headed model to predict different types of toxicity using Keras/TensorFlow.
4. **Evaluation**: Assessing model performance and generating predictions on test data.
5. **Submission**: Creating a formatted submission file for predictions.

## Installation

To get started, clone this repository and install the required packages:

'''bash
git clone https://github.com/your-username/toxicity-detection.git
cd toxicity-detection
pip install -r requirements.txt
'''

## Usage
Follow these steps to run the project:

Prepare the data:

Place train.csv and test.csv in the project directory.
Run the EDA Notebook:

Open EDA.ipynb in Jupyter Notebook or Jupyter Lab.
Run all cells to perform exploratory data analysis.
Train the Model:

Open model_training.ipynb.
Run all cells to preprocess data, build, and train the model.
Generate Predictions:

Run the prediction cells in model_training.ipynb.
The predictions will be saved in submission.csv.

## Data
The dataset consists of comments from Wikipedia's talk page edits, with labels indicating different types of toxicity:

toxic
severe_toxic
obscene
threat
insult
identity_hate

## Model Architecture
The model is a multi-headed neural network with shared LSTM layers and separate dense layers for each toxicity type. This architecture allows the model to learn common features while specializing in detecting specific types of toxicity.

## Exploratory Data Analysis
A comprehensive EDA is provided to understand the dataset better. Key steps include:

Analyzing target variable distribution.
Visualizing correlations between toxicity types.
Exploring comment length distribution.
Generating word clouds for toxic and non-toxic comments.
Identifying common words in toxic and non-toxic comments.

## Results
The model achieves impressive results in detecting various types of toxicity. Detailed performance metrics and visualizations are provided in the model_training.ipynb.

## Contributing
Contributions are welcome! Please fork this repository, create a new branch, and submit a pull request. Ensure your code adheres to the project's coding standards and includes relevant tests.

## Contact
For any questions or feedback, please feel free to reach out:

Email: samisanadi270@gmail.com
GitHub: mdsami313

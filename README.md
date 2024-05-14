# Final-Year-Project

## Introduction
This repository contains the code and related materials for my final year project, which focuses on predicting stock prices using various convolutional neural network (CNN) and multi-layer perceptron (MLP) models. The project is part of my dissertation work for my graduation thesis.

## Project Structure
The repository is organized into the following directories:

- `Dataset`: Contains the stock data used for training and testing the models.
- `Dissertation`: Includes the dissertation document detailing the research, methodology, results, and conclusions.
- `Experimental Results`: Contains the results of various experiments conducted during the project.
- `Model`: Includes the implementations of the different CNN-MLP models used in the project.
- `Proposal`: Contains the initial project proposal and planning documents.

## Data
The dataset used in this project consists of stock price data for the S&P 500 (SPX). The data is preprocessed to create sequences of stock prices for training the models. The data is split into training and test sets to evaluate the performance of the models.

## Models
This project implements and compares several versions of CNN-MLP models for stock prediction:

1. **CNN-MLP with Adam Optimizer**
2. **CNN-MLP with SGD Optimizer**
3. **CNN-MLP with AlexNet Architecture**
4. **CNN-MLP with ResNet (ResNet18) Architecture**

Each model is implemented in PyTorch and includes custom dataset classes, data loaders, and training loops.

## Training and Evaluation
The models are trained using sequences of stock price data. The training process involves:

- Data Loading and Preprocessing: Loading stock data, normalizing, and creating sequences.
- Model Definition: Defining the architecture of CNN-MLP models.
- Training: Training the models using the specified optimizers (Adam, SGD) and architectures (AlexNet, ResNet).
- Evaluation: Evaluating the models using metrics such as RMSE, MAE, and R².

### Training Process
1. **Data Preprocessing**: The data is normalized and sequences are created.
2. **Model Training**: Models are trained using PyTorch with different optimizers and architectures.
3. **Performance Metrics**: The performance is evaluated using RMSE, MAE, and R² scores.

### Evaluation Metrics
- **Root Mean Squared Error (RMSE)**
- **Mean Absolute Error (MAE)**
- **R-squared (R²)**

### Trading Strategy Simulation
- A trading strategy is simulated based on the model's predictions.
- The final return and annualized return are calculated to assess the strategy's effectiveness. 

## Experimental Results
The `Experimental Results` directory contains the results of the experiments conducted during the project. This includes plots of model performance, comparison of different models, and analysis of the results.
- Comparison of different optimization techniques (Adam vs. SGD).
- Performance analysis of models with AlexNet and ResNet architectures.
- Visualization of prediction accuracy and error metrics. 

## Dissertation
The dissertation document provides a detailed description of the research question, literature review, methodology, experimental setup, results, and conclusions. It follows the academic standards and formatting guidelines required by the university.

## Usage

To run the models and reproduce the results, follow these steps:

1. **Install Dependencies**:
   Ensure you have Python and the required libraries installed. You can use the provided `requirements.txt` to install dependencies:
   ```bash
   pip install -r requirements.txt

2. **Download Dataset**:
   Ensure the stock data is available in the Dataset directory. If necessary, download the required data and place it in the correct directory.

3. **Run Models**:
   Ensure you have Python and the required libraries installed. You can use the provided `requirements.txt` to install dependencies:
   ```bash
   cd Model
   python train_cnn_mlp_adam.py

4. **View Results**:
   Check the Experimental Results directory for plots and performance metrics. Analyze the results as described in the Results section. 

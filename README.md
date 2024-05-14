# Final-Year-Project

## Overview

This repository contains the code, data, and documentation for the Final Year Project of Changqing Lin, focusing on stock prediction using various CNN-MLP models. The project is part of the requirements for the Financial Technology program at Nanyang Technological University.

## Project Structure

The repository is organized into the following directories:

- **Dataset**: Contains the stock data used for model training and evaluation.
- **Dissertation**: Includes the various sections of the dissertation document.
- **Experimental Results**: Stores the results from different model experiments.
- **Model**: Contains the implementation of the CNN-MLP models and their variants.
- **Proposal**: Contains the project proposal and initial documentation.

## Methodology

The methodology for this project is detailed in the `Dissertation` section and includes the following key components:

1. **Data Collection and Preprocessing**:
   - Stock data from `XOM.csv` is loaded and preprocessed for use in the models.
   - Preprocessing steps include normalization and sequence generation.

2. **Model Architecture**:
   - The primary model is a CNN-MLP hybrid optimized using Adam and SGD.
   - Variants include replacing the CNN component with AlexNet and ResNet (ResNet18).
   - Each model architecture is detailed with mathematical notation and descriptive text.

3. **Training Procedure**:
   - Models are trained on sequences of stock data with specific hyperparameters.
   - The training process includes loss calculation, backpropagation, and optimization.

4. **Evaluation Metrics**:
   - Models are evaluated using RMSE, MAE, and R² metrics.
   - Performance metrics are computed on the test set, with results plotted for analysis.

5. **Trading Strategy Simulation**:
   - A trading strategy is simulated based on the model's predictions.
   - The final return and annualized return are calculated to assess the strategy's effectiveness.

## Results

Experimental results are documented in the `Experimental Results` directory. Key findings include:

- Comparison of different optimization techniques (Adam vs. SGD).
- Performance analysis of models with AlexNet and ResNet architectures.
- Visualization of prediction accuracy and error metrics.

## Dissertation

The `Dissertation` directory contains the complete dissertation document, including:

- Title page, abstract (in English and Chinese), and acknowledgements.
- Table of contents, lists of tables, figures, and abbreviations.
- Detailed sections on introduction, literature review, methodology, results, discussion, and conclusions.
- References following the Harvard or APA referencing style.
- Appendices with supplementary material.

## Usage

To run the models and reproduce the results, follow these steps:

1. **Install Dependencies**:
   Ensure you have Python and the required libraries installed. You can use the provided `requirements.txt` to install dependencies:
   ```bash
   pip install -r requirements.txt

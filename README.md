# Energy Consumption Prediction in the Greater Buenos Aires Area

## Master's Thesis Summary

This repository contains the code that supports the research conducted in the master's thesis titled **"Energy Consumption Prediction in the Greater Buenos Aires Area"**.

**Author:** Franco Ariel Demare
**Thesis Title:** Master in Data Intelligence oriented to Big Data
**Supervisor/Co-supervisor:** Prof. Dr. Aurelio F. Bariviera
**Thesis report:** You can find the complete thesis report Tesis_Predicción del consumo GBA.pdf
**Author's contact email:** frandemare@gmail.com

## Motivation

The main motivation of this work lies in the growing need to accurately predict electricity demand due to rapid economic expansion and increased energy consumption, both industrial and domestic. Accurate consumption prediction is essential to optimize resource management, reduce costs, and minimize environmental impact, in line with the Sustainable Development Goals (SDGs).

## Methodology

In this research, statistical and machine learning models were explored and compared for energy consumption prediction:

* **Statistical Models:**
    * Linear Regression
    * Regression Trees
    * Autoregressive Moving Average (ARIMA) Model
    * SVM Model
* **Machine Learning Models:**
    * Long Short-Term Memory (LSTM)
    * Convolutional Neural Network (CNN)
    * CNN-LSTM Models

Historical energy consumption data was used to train and evaluate these models, with special attention to the time series nature of the data and **seasonality**. The use of the **Empirical Mode Decomposition (EMD)** technique to improve the performance of the LSTM model by decomposing the time series into intrinsic components is specifically mentioned.

## Results

The research concluded with the evaluation of the performance of the different models. The **LSTM model combined with the EMD technique (LSTM-EMD)** proved to be the most effective for energy consumption prediction in the evaluated forecast horizon (201 hourly observations). This model outperformed the predictions made by CAMMESA for the same period.

## Keywords

Machine learning; Statistical model; Energy consumption; Neural networks; Time series; Prediction.

## Repository Content

This repository contains the source code developed for the implementation and evaluation of the prediction models described in the thesis. You will find scripts for:

* Data preprocessing and cleaning.
* Implementation of statistical models.
* Implementation of machine learning models (including EMD integration with LSTM).
* Training and evaluation of models using relevant metrics.
* Visualization of results and comparisons between models.

The code is mainly developed in Python and makes use of libraries such as [**pandas, numpy, scikit-learn, TensorFlow, Keras, statsmodels, etc.**].

## How to Use

To run the code in this repository, make sure you have a Python environment installed, such as Anaconda or Google Colab.

It is recommended to follow these steps:

1.  Clone this repository.
2.  Create a virtual environment (optional) and install the necessary dependencies.
3.  Run the scripts in the "Visualización de datos diarios" directory to visualize the daily dataset.
4.  Run the scripts in the "Implementación de modelos con datos diarios" directory to understand the justifications of the thesis.
5.  Run the scripts in the "Implementación de EMD a modelos LSTM y CNN con datos diarios e intradiarios" directory to see a real use case of the best trained model.

## Contact

frandemare@gmail.com

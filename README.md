# 🍄 Mushroom Classification

This project focuses on building a machine learning model to classify mushrooms as edible or poisonous. The classification is performed using neural networks as well as a random forest classifier to compare the performance of the two models.

## Project Overview

Mushroom classification is a critical task in ensuring safety when identifying edible mushrooms. This project leverages advanced machine learning techniques to achieve accurate classification.

## Dataset

The dataset was acquired from the UC Irvine Machine Learning Repository and contains various features of mushrooms, such as cap shape, color, and odor. Each mushroom is labeled as either edible or poisonous.

## Project Workflow

1. **Data Import and EDA:**
    - Fetch data from UCI repo 
    - Basic EDA to understand dataset 
2. **Data Preprocessing**:
    - Impute missing values 
    - Encode all categorical features
    - Label encode reponse variable 
3. **Model Training:**
    - Build and train a neural network model
    - Build and train a random forest classifier 
4. **Model Evaluation:**
    - Visualize model performance using Confusion Matrix 
    - Assess the model's performance using metrics like accuracy and F1-score.
5. **Model Comparison & Selection:**
    - Compare metrics on both models to select best model


## Requirements

- Python 3.8 and above
- Libraries: NumPy, pandas, scikit-learn, TensorFlow/Keras, matplotlib

## Results

The results of the model, including accuracy and visualizations, will be documented here.

## Future Work

- Experiment with other dimensionality reduction techniques.
- Optimize the neural network architecture.
- Deploy the model as a web application.

## License

This project is licensed under the MIT License.

# 🍄 Mushroom Classification

This project focuses on building a machine learning model to classify mushrooms as edible or poisonous. The classification is performed using neural networks as well as a random forest classifier to compare the performance of the two models.

## Project Overview

Mushroom classification is a critical task in ensuring safety when identifying edible mushrooms. This project leverages advanced machine learning techniques to achieve accurate classification.

## Dataset

The dataset was acquired from the UC Irvine Machine Learning Repository and contains various features of mushrooms, such as cap shape, color, and odor. Each mushroom is labeled as either edible or poisonous.

## Project Workflow

1. **Data Import and EDA:**
    - Handle missing values.
    - Encode categorical features.
2. **Data Preprocessing**:
    - Apply PCA to reduce dimensionality.
3. **Model Training:**
    - Build and train a neural network model
    - Build and train a random forest classifier 
4. **Model Evaluation:**
    - Assess the model's performance using metrics like accuracy and F1-score.
5. **Model Comparison & Selection:**
    - 


## Requirements

- Python 3.x
- Libraries: NumPy, pandas, scikit-learn, TensorFlow/Keras, matplotlib

## How to Run

1. Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the training script:
    ```bash
    python train_model.py
    ```

## Results

The results of the model, including accuracy and visualizations, will be documented here.

## Future Work

- Experiment with other dimensionality reduction techniques.
- Optimize the neural network architecture.
- Deploy the model as a web application.

## License

This project is licensed under the MIT License.

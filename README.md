# phone_price_prediction
This repository uses machine learning to predict smartphone prices based on features like camera, processor, and battery. Models such as Random Forest and LightGBM achieved over 88% accuracy. Future work includes improving feature engineering and exploring neural networks. 


For your **Phone Price Prediction** project, here's an outline of what to include in your GitHub README file:

---

# Phone Price Prediction

## Overview

This project involves predicting the price of smartphones based on their features such as camera specifications, processor type, RAM, ROM, battery capacity, display size, and user ratings. The goal is to develop a predictive model that helps users estimate the price of a phone based on its attributes.

## Problem Statement

With the increasing variety of smartphones available in the market, it can be difficult for users to determine the price based on key specifications. This model uses historical smartphone data to predict prices for new models based on their features.

## Dataset

The dataset used in this project contains details about various smartphones, including:

- **Camera**: Camera specifications (e.g., megapixels)
- **Processor**: Processor type and details
- **Price**: The price of the phone (target variable)
- **Rating**: User ratings on the phone
- **Reviews**: Number of reviews
- **Battery**: Battery capacity (mAh)
- **RAM**: RAM size (GB)
- **ROM**: Storage capacity (GB)
- **Expandable Memory**: Expandable memory capacity (GB)
- **Display Size**: Screen size in inches

## Model

In this project, I applied machine learning techniques such as **Random Forest** and **LightGBM** to predict the price of smartphones based on the aforementioned features. The models were trained, evaluated, and optimized to achieve a reliable prediction.

## Features

- **Random Forest Model**: A robust ensemble learning method that combines multiple decision trees to make predictions.
- **LightGBM Model**: A gradient boosting framework that efficiently handles large datasets and categorical features.
- **Feature Engineering**: Data preprocessing steps such as handling missing values, encoding categorical variables, and scaling numerical features.

## Accuracy

- **Random Forest**: Achieved an accuracy of around 87-88%.
- **LightGBM**: Achieved an accuracy of 84%.

## Installation

To run this project locally, follow these steps:

1. Clone this repository:

    ```bash
    git clone https://github.com/your-username/phone-price-prediction.git
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the project:

    ```bash
    python predict_price.py
    ```

## Results

The model provides predicted prices based on input features, which can be tested with new phone data.

## Future Improvements

- Enhance feature engineering, particularly by analyzing and encoding complex categorical features (e.g., camera specifications).
- Experiment with deep learning models or other advanced regression techniques.
- Use a more detailed dataset for improved model accuracy.

## License

This project is licensed under the MIT License.

---

This README will give visitors to your repository a clear idea of what the project does, how to use it, and what they can expect from it. Feel free to modify it based on your project’s specific details!

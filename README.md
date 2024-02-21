# Breast Cancer Analyzer

The Breast Cancer Diagnosis app is a machine learning-powered tool designed to assist medical professionals in diagnosing breast cancer. It utilizes a set of measurements to predict whether a breast mass is benign or malignant. The app provides a visual representation of the input data using a radar chart and displays the predicted diagnosis along with the probability of being benign or malignant.

## Features

- **Prediction**: Predicts whether a breast mass is benign or malignant based on input measurements.
- **Visual Representation**: Provides a radar chart visualizing the input data.
- **Manual Input**: Allows manual input of measurements.
- **Integration**: Can be connected to a cytology lab machine to obtain data directly.

## Dataset

The app was developed using the [Breast Cancer Wisconsin (Diagnostic)](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data) Dataset, a public dataset commonly used in machine learning exercises. However, it's important to note that this dataset may not be reliable for professional use, as the project was developed solely for educational purposes in the field of machine learning.

## Deployment
The app is deployed on [Streamlit](https://streamlit.io/), a Python-based web app framework. A live version of the application can be found on [Streamlit Community Cloud](https://breast-cancer-analyzer-3gc4kywq43sj2swor3myvn.streamlit.app/).

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your_username/Breast-Cancer-Diagnosis-App.git
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

To run the app, execute the following command:

```bash
streamlit run app/main.py
```

This will launch the app in your default web browser.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Disclaimer

The Breast Cancer Diagnosis app is intended for educational purposes only and should not be used for professional medical diagnosis. The predictions made by the app are based on a machine learning model trained on publicly available data and may not be accurate for real-world medical scenarios.

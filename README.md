# Deep-STOC: Deep Learning for Offshore Earthquake Prediction

## Overview

This repository contains the code used in the MSC dissertation "Deep-STOC: Deep Learning for Offshore Earthquake Prediction". The research focuses on predicting earthquakes in the Aegean Sea using remote sensing data from Copernicus' ocean colour changes. It presents a deep learning model, Deep-STOC, that uses a convolutional long short-term memory (ConvLSTM) architecture to process the spatiotemporal aspects of the data.

## Directory Structure

- `data_engineering/`: Contains the Jupyter notebook `data_engineering.ipynb` used for data cleaning, preprocessing, and exploration.
- `models/`: Contains two Jupyter notebooks:
    - `Deep-STOC_model_implementation.ipynb`: Implements the Deep-STOC model.
    - `Deep-STOC_tuning.ipynb`: Performs hyperparameter tuning on the Deep-STOC model.

## Key Findings

- The research demonstrates the potential of using ocean colour changes as an earthquake precursor.
- The proposed ConvLSTM model, Deep-STOC, shows promising results across key metrics, proving its viability for offshore earthquake prediction.
- This research contributes to the field by pioneering the use of remote sensing ocean colour data for offshore earthquake prediction.

## Potential Future Work

- Refine data quality and interpolation processes.
- Explore different model configurations.
- Extend the model's application to other geographically prone areas to seismic activity.

## Usage

To understand the code structure and approach:

1. Clone the repository.
2. Review the `data_engineering.ipynb` notebook for understanding the steps involved in data cleaning, preprocessing, and exploration.
3. Review the `Deep-STOC_model_implementation.ipynb` notebook for understanding the implementation of the Deep-STOC model.
4. Review the `Deep-STOC_tuning.ipynb` notebook to understand the hyperparameter tuning process.

Please note that the raw data used in this project is not available in this repository. The code provided in the repository is for demonstration of the methodology and approach, and may require modifications if used with other datasets.

## Dependencies

- Python 3.7+
- TensorFlow 2.5+
- Keras
- Keras Tuner
- Scikit-learn
- NumPy
- Pandas
- Google Colab

Please ensure all dependencies are installed and up-to-date.

## Contribution

Contributions are welcome! If you'd like to improve the model, add new features or find any bugs, feel free to fork this repository, make changes, and submit a pull request.

## Contact

If you have any questions or suggestions, please reach out.

Thank you for visiting!

This project is a part of an MSC dissertation and serves as a significant step towards real-world applications of machine learning in disaster preparedness and mitigation.

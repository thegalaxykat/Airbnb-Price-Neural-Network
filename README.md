# A Neural Network to Predict Airbnb Listing Nightly Prices

This repository contains a Jupyter notebook that implements a neural network to predict nightly prices for Airbnb listings. The model is built using Python, `sklearn`, and `Keras` (an API for TensorFlow).

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Predicting the nightly prices of Airbnb listings can be beneficial for hosts to set competitive prices and for guests to find the best deals. This project aims to build a neural network model that accurately predicts these prices based on various features of the listings.

## Installation

To run this project, you need to have Python installed. It is recommended to use a virtual environment to manage dependencies. Follow the steps below to set up the environment and install the required packages:

1. Clone the repository:
    ```bash
    git clone https://github.com/thegalaxykat/airbnb-price-prediction.git
    cd airbnb-price-prediction
    ```

2. Create a virtual environmentn with your method of choice.

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Unzip the data file:
    - The data file is located in the `data` directory and needs to be unzipped before use.

2. Open the Jupyter notebook:
    ```bash
    jupyter notebook
    ```

3. Run the notebook:
    - Open `Airbnb_Price_Prediction.ipynb` and run all cells to train the model and make predictions.

## Data

The data used in this project is attached to the repository. It needs to be unzipped before use. The dataset includes various features of Airbnb listings such as location, number of bedrooms, availability, and more.

## Model

The model is built using a neural network implemented with Keras. The process is explained in detail in the Jupyter notebook as the problem is worked through.

### Key Components:

- **Data Preprocessing**: Handling missing values, encoding categorical variables, and scaling numerical features.
- **Model Architecture**: A multi-layer neural network with dropout and L2 regularization.
- **Training**: Using Mean Squared Error (MSE) as the loss function and Adam optimizer.
- **Evaluation**: Metrics such as MAE, RMSE, and R² are used to evaluate the model's performance.

## Results

The model's performance is evaluated using the following metrics:

- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**
- **R-squared (R²)**

The results are discussed in the notebook with visualizations to illustrate the model's performance.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. For major changes, please open an issue first to discuss what you would like to change. One thing I didn't get to is adding amenities to the model which I think could be really interesting.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

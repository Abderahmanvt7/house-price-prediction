# House Price Prediction Project

This project aims to predict house prices using a linear regression model based on various features such as the number of bedrooms, bathrooms, square footage, etc.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

Linear regression is a simple yet powerful machine learning technique used for predicting continuous values. In this project, we utilize linear regression to predict house prices based on a dataset containing various features of houses such as the number of bedrooms, bathrooms, square footage, etc.

## Dataset

The dataset used for this project contains information about houses including their features and corresponding prices. It includes the following columns:

- **id**: Unique identifier for each house
- **date**: Date the house was sold
- **price**: Sale price of the house
- **bedrooms**: Number of bedrooms
- **bathrooms**: Number of bathrooms
- **sqft_living**: Square footage of the living area
- **sqft_lot**: Square footage of the lot
- **floors**: Number of floors
- **waterfront**: Whether the house has a waterfront view (binary: 0 or 1)
- **view**: Number of times the house has been viewed
- **condition**: Overall condition of the house
- **grade**: Overall grade given to the housing unit
- **sqft_above**: Square footage of house apart from the basement
- **sqft_basement**: Square footage of the basement
- **yr_built**: Year the house was built
- **yr_renovated**: Year the house was renovated
- **zipcode**: Zip code of the area
- **lat**: Latitude coordinate of the house
- **long**: Longitude coordinate of the house
- **sqft_living15**: Square footage of the living area of the nearest 15 neighbors
- **sqft_lot15**: Square footage of the lot of the nearest 15 neighbors

## Installation

To run the code locally, you'll need Python 3.x and the following libraries:

- numpy
- pandas
- matplotlib
- scikit-learn

You can install these dependencies using pip:

```bash
pip install numpy pandas matplotlib scikit-learn
```

## Usage

1. Clone the repository to your local machine:

```bash
git clone git@github.com:Abderahmanvt7/house-price-prediction.git
```

2. Navigate to the project directory:

```bash
cd house-price-prediction
```

3. Run the Jupyter notebook house_price_prediction.ipynb to train the linear regression model and make predictions.

4. Modify the code as needed or experiment with different models and parameters.

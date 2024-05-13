
# Analyzing the Relationship Between GDP per Capita and Life Satisfaction

This project aims to analyze the relationship between GDP per capita and life satisfaction using a linear regression model. The analysis involves visualizing the data, training a linear regression model, and making predictions.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Results](#results)


## Introduction

This project demonstrates how to use a simple linear regression model to explore the relationship between GDP per capita and life satisfaction. By plotting the data and making predictions, we can gain insights into how economic factors might influence subjective well-being.

## Dataset

The dataset used in this project contains information on GDP per capita and life satisfaction for various countries. The data is stored in a pandas DataFrame named `lifesat` with the following columns:

- `GDP per capita (USD)`: The GDP per capita in US dollars.
- `Life satisfaction`: The life satisfaction score.

## Dependencies

To run this project, you will need the following Python libraries:

- `pandas`
- `matplotlib`
- `scikit-learn`

You can install the dependencies using pip:

```bash
pip install pandas matplotlib scikit-learn
## Usage

1. Clone the repository or download the notebook file.

2. Ensure you have the necessary dependencies installed.

3. Load your dataset into a pandas DataFrame named `lifesat` with the appropriate columns.

4. Run the notebook to perform the analysis. The main steps include:
   - Visualizing the data with a scatter plot.
   - Training a linear regression model.
   - Making predictions based on the trained model.
   - Visualizing the prediction on the scatter plot.

## Results

The analysis provides a visual representation of the relationship between GDP per capita and life satisfaction. The linear regression model allows us to predict life satisfaction based on GDP per capita, which is visualized on the scatter plot.


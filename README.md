# Comparative Analysis of Time Series and Machine Learning Models for Forecasting Grocery Prices

This repository contains all implementations of the models employed in the bachelor's thesis “Comparative Analysis of Time Series and Machine Learning Models for Forecasting Grocery Prices”.

## Installation

Install required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

### Time Series Forecasting Models

To reproduce the results from the thesis:

1. Open `time_series_models.ipynb`
2. In the first cell, specify the file path to the according file
3. Set the appropriate sequence length for the LSTM model based on your product:

   | Product                  | Sequence Length |
   | ------------------------ | --------------- |
   | Pesto                    | 80              |
   | Chicken Breast           | 140             |
   | Coffee                   | 150             |
   | Butter                   | 65              |
   | Noodles                  | 110             |
   | Weekly Butter (Agridata) | 76              |

4. Execute all cells in order

**Important Note**:

- After running the LSTM model, delete the automatically created folder named "untitled_project". This folder contains hyperparameter tuning results that may interfere with subsequent runs if not removed.

### Markov Chain

Open the file `markov_chain.ipynb` and execute all cells

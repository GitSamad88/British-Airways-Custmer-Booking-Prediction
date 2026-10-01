# Customer Booking Prediction

This project analyzes and predicts whether a customer will complete a booking based on booking and travel-related features.

## Project overview

The workflow includes:
- data cleaning and preprocessing
- feature selection
- model training and evaluation
- hyperparameter tuning
- saving the reduced dataset for downstream modeling

## Folder structure

- `data/` — dataset files
- `notebooks/` — analysis, feature selection, and model training notebooks
- `report/` — generated reports or outputs

## Data

The main cleaned dataset is:
- `data/Custmer_Booking_clean_data.csv`

The reduced feature-selected dataset is:
- `data/customer_booking_after_feature_selection.csv`

## Setup

1. Create a Python virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate   # Linux/macOS
   .venv\Scripts\activate      # Windows
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebooks in Jupyter or VS Code.

## Recommended notebooks

- `notebooks/Custmer Booking - Feature Selection.ipynb`
- `notebooks/Custmer Booking  Model Training & HyperTunning.ipynb`

## Run

Open the notebook and run the cells in order from top to bottom.

## Notes

- The notebook paths assume the project root is the folder containing `data/` and `notebooks/`.
- If you encounter path issues, run the notebook from the project root or update the CSV paths to match your current working directory.

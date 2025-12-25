# Customer Churn Prediction using ANN

This project demonstrates a binary classification problem using Artificial Neural Networks (ANN) to predict customer churn.

## Project Structure

- `experiments.ipynb`: Jupyter notebook for data preprocessing, model training, and evaluation.
- `predictions.ipynb`: Jupyter notebook for making predictions with the trained model.
- `app.py`: Streamlit web application for interactive predictions.
- `model.h5`: The trained Keras model.
- `*.pkl`: Pickled preprocessors (scalers, encoders).

## Setup

1. Create a virtual environment:
   ```bash
   python -m venv venv
   ```

2. Activate the virtual environment:
   - Windows: `venv\Scripts\activate`
   - Mac/Linux: `source venv/bin/activate`

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

To run the Streamlit app:
```bash
streamlit run app.py
```

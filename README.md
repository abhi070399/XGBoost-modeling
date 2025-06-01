# XGBoost Modeling for Groundwater Prediction

This repository contains code for predicting groundwater levels using the XGBoost machine learning algorithm. The model is trained on environmental and hydrological data to support sustainable groundwater management and trend analysis.

## Repository Contents
- `notebook/` – Jupyter notebooks used for preprocessing, training, and evaluation  
- `data/` – Sample dataset  
- `scripts/` – Python scripts for reproducibility    
- `README.md` – This file  
- `requirements.txt` – List of dependencies  

## Installation

To run this code, ensure you have Python 3.8 or above installed.

1. Clone this repository:
   ```
   git clone https://github.com/abhi070399/XGBoost-modeling
   cd XGBoost-modeling
   ```

2. (Optional) Create a virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install required packages:
   ```
   pip install -r requirements.txt
   ```

## How to Run the Code

Open the Jupyter notebook file in the `notebook/` directory:
```
jupyter notebook Groundwater_XGBoost_Model.ipynb
```
Follow the instructions in the notebook to load the data, train the model, and evaluate performance.

## Quick Test

To verify the installation and check if the environment is working, run:
```
python test/test_model.py
```

## Dependencies

- Python >= 3.8  
- numpy  
- pandas  
- scikit-learn  
- xgboost  
- matplotlib  
- seaborn  

## Citation

If you use this code in your research, please cite it as:

Maurya, A. (2025). XGBoost Modeling for Groundwater Prediction. GitHub. https://github.com/abhi070399/XGBoost-modeling


## Contact

For any questions or support, please contact:  
Abhishek Maurya – abhi99maurya@gmail.com


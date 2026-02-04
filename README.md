# Statistical Inference & Gaussian Processes

The notebook walks through:
- Bayesian vs. frequentist estimation on a coin-flip dataset.
- Variance reduction with importance sampling.
- Variational inference for logistic regression.
- HMC/NUTS benchmark in NumPyro.
- Gaussian process regression (Bayesian Optimisation) for tabular data.

This project was completed as part of my MSc module **Reasoning and Learning Under Uncertainty**. 

Grade: 91/100

## Files
- `full_notebook.ipynb` — the main notebook containing all the VI and BO code.
- `datasets_part_1/` — small CSVs used in the notebook.
- `requirements.txt` — all python packages required for the program.

## Running the notebook locally
To execute cells:
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```



# CS 6220 — Homework 1

Sets up a data mining environment and builds a scikit-learn pipeline to
classify Iris flowers by species.

## Contents

- `homework_1.ipynb` — data loading, scatterplot, train/test split,
  pipeline (StandardScaler + LogisticRegression), training, evaluation,
  confusion matrix.

## Environment

- Python 3, Jupyter Lab, run locally on Windows in a `venv`
- Libraries: scikit-learn, pandas, matplotlib

## How to Run

```
git clone https://github.com/shahana-neu/CS6220.git
cd CS6220
python -m venv venv
.\venv\Scripts\Activate
pip install -r requirements.txt
jupyter lab
```

Open `homework_1.ipynb` and run all cells.

## Results

- Training time: 0.0146 seconds
- Testing time: 0.0027 seconds
- Test accuracy: 1.0000 (100%)

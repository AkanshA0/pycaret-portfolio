# Anomaly Detection (PyCaret 3.x)

This folder contains a PyCaret 3.3.2 notebook demonstrating anomaly detection (Isolation Forest) on an unlabeled credit card fraud dataset.
download dataset from https://www.kaggle.com/datasets/kartik2112/fraud-detection/data?select=fraudTrain.csv in the anomaly folder.

Contents
- `anomaly_colab.ipynb` — Jupyter notebook that: loads the training set, sets up PyCaret anomaly detection, creates an Isolation Forest model, assigns anomalies, and runs predictions on the test set.
- `fraudTrain.csv` — training data used by the notebook.
- `fraudTest.csv` — test data used for prediction/demo.

Quick notes
- Data paths in the notebook are relative to this folder, e.g. `./anomaly/fraudTrain.csv` and `./anomaly/fraudTest.csv`.

Minimal requirements
- Python 3.8+ (match your environment)
- pandas
- pycaret (tested with PyCaret 3.x in the notebook)

Install

    pip install pandas pycaret

The notebook sets `use_gpu=True` in `setup()`, this should be enabled only if your environment supports it.

How to run
1. Open `anomaly_colab.ipynb` in Jupyter or Colab.
2. Verify the notebook's data path (it expects the CSVs in `./anomaly/`).
3. Run cells top-to-bottom. The notebook creates and saves an Isolation Forest pipeline.

# PyCaret Portfolio (Starter Structure)

This repository contains PyCaret notebooks for for different usecases. The notebooks were executed in windows (Jupyter).

## How to use
- Install pycaret 3.3.2
- Start Jupyter lab in **pycaret-portfolio** folder (otherwise dataset loading will throw path error).
- Keep `use_gpu=True` in `setup(...)` where applicable and turn GPU **on** in Colab (`Runtime → Change runtime type → GPU`).

## Tree
- `classification_binary/` – Binary classification
- `classification_multiclass/` – Multiclass classification
- `regression/` – Regression
- `clustering/` – Clustering
- `anomaly/` – Anomaly detection
- `association_rules_pycaret235/` – Association rules (separate env - PyCaret **2.3.5**)
- `time_series/` – Time series (univariate ± exogenous)
- `gradio_demos/` – Two simple Gradio app starters


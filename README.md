# NASA Lithium Ion Battery RUL Prediction using Neural Networks

This repository contains a Jupyter notebook for predicting Remaining Useful Life (RUL) of NASA's Lithium Ion batteries using Neural Networks. The notebook is based on two datasets:

- `BATTERY_RUL.csv`: This dataset contains the RUL of each battery cycle.
- `NASA_LiIon_Battery_Cycles.csv`: This dataset contains the operational data of the batteries including inputs and capacity.

## Dataset

The dataset used in this notebook is the [NASA Li-Ion Battery Dataset](https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#li-ion-battery), which consists of operational data of the batteries including inputs and capacity, and the RUL of each cycle. The dataset is available in the `data` subdirectory of this repository as two separate CSV files named `BATTERY_RUL.csv` and `NASA_LiIon_Battery_Cycles.csv`.

## Notebook

The notebook is implemented using Python, and uses the TensorFlow library for building and training the neural network model. It is hosted on Google Colab, and can be accessed through the following link:

[NASA Lithium Ion Battery RUL Prediction Notebook]
https://colab.research.google.com/drive/1cG2j3m-uADxSsr229g56Eo55DSaxDT0p?usp=sharing

The notebook includes the following sections:

1. Data Preparation
2. Feature Selection and Engineering
3. Model Building
4. Model Training and Evaluation
5. Results Visualization

The notebook provides detailed explanations of each step, as well as code snippets for implementing them.

## How to Use

To use this notebook, simply click on the link above to open it in Google Colab. You can then run each cell of the notebook in order to reproduce the results presented in the notebook.

## Credits

This notebook was created by [Drhorhi Omar], and is licensed under the MIT License. The dataset used in this notebook is from the [NASA Prognostics Center of Excellence].

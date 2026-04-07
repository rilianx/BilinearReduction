# Greedy Bilinear Reduction via Diagonal Budgeting for Improved Affine Arithmetic Bounds

This repository contains the source code and datasets required to reproduce the experiments presented in the research paper: **"Greedy Bilinear Reduction via Diagonal Budgeting for Improved Affine Arithmetic Bounds"**.

The code implements the *diagonal budgeting* algebraic rewriting strategy proposed in the paper. It allows for the empirical evaluation of how this mechanism minimizes the linear approximation error and consequently tightens Affine Arithmetic (AA) bounds for quadratic forms.

## 📂 Repository Contents

* `experiments.ipynb`: An interactive Jupyter Notebook containing the main code to run the benchmarks, apply the Two-Bag greedy algorithm, and generate the results and tables presented in the paper.
* `requirements.txt`: List of Python dependencies required to run the code.

## ⚙️ Requirements and Dependencies

To run the notebook, you need **Python 3.8+**.

You can install all dependencies via `pip` by running:
```bash
pip install -r requirements.txt

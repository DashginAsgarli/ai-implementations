# AI Implementations

> ML, DL, NLP and CV models implemented from scratch and with scikit-learn/PyTorch.

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![PyTorch](https://img.shields.io/badge/PyTorch-DL%20%26%20CV-ee4c2c.svg)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-f7931e.svg)
![Status](https://img.shields.io/badge/status-in%20progress-yellow.svg)

## Overview

This repository is a collection of machine learning, deep learning and computer vision models that I built while learning data science. The core idea is simple: **understand a model by building it yourself, then compare it with the standard library version.**

For many models, the repository contains two implementations:

- **From scratch**: written with NumPy or PyTorch, without high-level model APIs (training loops, loss functions and metrics included).
- **With libraries**: the same task solved with scikit-learn or PyTorch building blocks, used as a reference and for comparison.

All experiments are done on real datasets, not toy examples.


## Tech Stack

- **Language:** Python
- **Core:** NumPy, Pandas
- **ML:** scikit-learn
- **DL / CV:** PyTorch, torchvision
- **Visualization:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook / Google Colab

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/DashginAsgarli/ai-implementations.git
   cd ai-implementations
   ```

2. Create a virtual environment and install dependencies:

   ```bash
   python -m venv venv
   source venv/bin/activate      # Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. Launch Jupyter and open any notebook:

   ```bash
   jupyter notebook
   ```

> Datasets and trained weights are not stored in this repository. Each notebook includes a link or instructions for obtaining the data.

## Approach

For every model, the notebooks follow the same structure:

1. **Problem and data**: what is being solved and what the data looks like
2. **Theory in brief**: the key idea and equations
3. **Implementation**: the model written step by step
4. **Training and evaluation**: loss curves, metrics, sample predictions
5. **Comparison**: results against the library implementation (where applicable)


## Contributing

Suggestions and feedback are welcome. Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


---

_This repository is a work in progress and is updated regularly._

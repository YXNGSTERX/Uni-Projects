# Uni-Projects

This repository contains coursework projects. The current project is a FashionMNIST deep learning lab under `Introduction_to_AI`.

## Project: Introduction to AI - FashionMNIST Lab

This project trains and evaluates a Convolutional Neural Network (LeNet-style) on the FashionMNIST dataset using PyTorch.

### Contents

- `Introduction_to_AI/FashionMINIST_lab2.ipynb`: Original lab notebook
- `Introduction_to_AI/Improved-FashionMINIST_lab2.ipynb`: Improved notebook with model/training refinements
- `Introduction_to_AI/Lab_Report_312023704026(2).pdf`: Project report

## Tech Stack

- Python 3
- PyTorch
- torchvision
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/YXNGSTERX/Uni-Projects.git
   cd Uni-Projects
   ```

2. (Recommended) Create and activate a virtual environment:

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

3. Install dependencies:

   ```bash
   pip install torch torchvision numpy pandas matplotlib seaborn scikit-learn jupyter torchsummary
   ```

## Run

1. Start Jupyter:

   ```bash
   jupyter notebook
   ```

2. Open one of the notebooks in `Introduction_to_AI/`.

3. Run cells from top to bottom.

## Notes

- If CUDA is available, the notebook uses GPU automatically.
- The dataset is downloaded automatically where `download=True` is set in the notebook.

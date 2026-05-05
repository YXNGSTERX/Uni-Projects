# Uni-Projects

A collection of university coursework projects covering Artificial Intelligence and Linux system administration.

---

## Projects

### 1. Introduction to AI — FashionMNIST Lab

Trains and evaluates a Convolutional Neural Network (LeNet-style) on the FashionMNIST dataset using PyTorch.

**Contents**

| File | Description |
|------|-------------|
| `Introduction_to_AI/FashionMINIST_lab2.ipynb` | Original lab notebook |
| `Introduction_to_AI/Improved-FashionMINIST_lab2.ipynb` | Improved notebook with model/training refinements |
| `Introduction_to_AI/Lab_Report_312023704026(2).pdf` | Project report |

**Tech Stack**

- Python 3, PyTorch, torchvision
- numpy, pandas, matplotlib, seaborn, scikit-learn

**Setup & Run**

```bash
# 1. Clone the repo
git clone https://github.com/YXNGSTERX/Uni-Projects.git
cd Uni-Projects

# 2. Create and activate a virtual environment (recommended)
python3 -m venv .venv
source .venv/bin/activate

# 3. Install dependencies
pip install torch torchvision numpy pandas matplotlib seaborn scikit-learn jupyter torchsummary

# 4. Launch Jupyter and open a notebook under Introduction_to_AI/
jupyter notebook
```

> **Notes:** If CUDA is available the notebook uses the GPU automatically. The FashionMNIST dataset is downloaded automatically on first run.

---

### 2. Linux — Lab Reports

Lab exercises covering core Linux and shell skills.

| Lab | Topic | Report |
|-----|-------|--------|
| Lab 1 | Linux GUI | `LInux/Lab1-Linux GUI/Linux2026_lab1_312023704026.docx` |
| Lab 3 | File contents operations | `LInux/Lab3-File contents operations/Linux2026_lab3_312023704026.pdf.pdf` |
| Lab 4 | Vim tutorial | `LInux/Lab4-Vim tutorial/Linux2026_lab4_312023704026.pdf` |
| Lab 5 | Special characters | `LInux/Lab5-Special characters/Linux2026_lab5_312023704026(2).docx` |
| Lab 6 | Basic shell commands | `LInux/Lab6-Basic shell commands/Linux2026_lab6_312023704026.docx` |

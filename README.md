# Intro to Statistical Learning — Python Labs

My worked solutions to the labs in **_An Introduction to Statistical Learning, with Applications in Python_** (ISLP) by James, Witten, Hastie, Tibshirani, and Taylor.

The goal of this repository is to build a solid, hands-on foundation in statistical learning: working through each lab, experimenting beyond the provided code, and documenting what I learn along the way.

> 📖 The book is available for free from the authors at [statlearning.com](https://www.statlearning.com/).

---

## Progress

| Chapter | Topic | Lab |
|:-------:|-------|:---:|
| 2  | Statistical Learning                         | ✅ |
| 3  | Linear Regression                            | 🚧 |
| 4  | Classification                               | ⬜ |
| 5  | Resampling Methods                           | ⬜ |
| 6  | Linear Model Selection and Regularization    | ⬜ |
| 7  | Moving Beyond Linearity                      | ⬜ |
| 8  | Tree-Based Methods                           | ⬜ |
| 9  | Support Vector Machines                      | ⬜ |
| 10 | Deep Learning                                | ⬜ |
| 11 | Survival Analysis and Censored Data          | ⬜ |
| 12 | Unsupervised Learning                        | ⬜ |
| 13 | Multiple Testing                             | ⬜ |

✅ complete &nbsp;·&nbsp; 🚧 in progress &nbsp;·&nbsp; ⬜ not started

---

## Repository Structure

Each chapter's lab lives in its own folder:

```
ISLP/
├── ch02_statistical_learning/
├── ch03_linear_regression/
├── ...
├── requirements.txt
└── README.md
```

---

## Getting Started

**1. Clone the repository**

```bash
git clone https://github.com/ToddMcKnight/Intro_to_statistical_learning_labs.git
cd Intro_to_statistical_learning_labs
```

**2. Create and activate a virtual environment**

```bash
python -m venv .venv
```

```powershell
# Windows (PowerShell)
.venv\Scripts\activate
```

```bash
# macOS / Linux
source .venv/bin/activate
```

**3. Install dependencies**

```bash
pip install -r requirements.txt
```

The book's companion package, [`ISLP`](https://pypi.org/project/ISLP/), provides the datasets and helper functions used throughout the labs.

---

## Tools

- **Python** — NumPy, pandas, matplotlib
- **Modeling** — statsmodels, scikit-learn, PyTorch (Chapter 10)
- **Book package** — `ISLP`

---

## Acknowledgments

All lab material is based on _An Introduction to Statistical Learning, with Applications in Python_ (Springer, 2023) by Gareth James, Daniela Witten, Trevor Hastie, Robert Tibshirani, and Jonathan Taylor. This repository contains my own work and notes; the book and its original lab code belong to the authors.

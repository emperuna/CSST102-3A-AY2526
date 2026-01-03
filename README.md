<h1 align="center">CSST 102 — Basic Machine Learning</h1>

<p align="center">
  <strong>Academic Portfolio • BSCS 3A • AY 2025-2026</strong>
</p>

<p align="center">
  <a href="#overview">Overview</a> •
  <a href="#coursework">Coursework</a> •
  <a href="#technologies">Technologies</a> •
  <a href="#getting-started">Getting Started</a> •
  <a href="#author">Author</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-learn">
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter">
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS">
</p>

---

## Overview

This repository contains coursework, exercises, and projects for **CSST 102: Basic Machine Learning**. The portfolio demonstrates practical implementations of fundamental machine learning concepts including supervised learning, model evaluation, and regression analysis.

### Learning Objectives

- Apply data preprocessing and feature engineering techniques
- Implement classification and regression algorithms
- Evaluate model performance using industry-standard metrics
- Understand cross-validation and model selection

---

## Coursework

| Activity     | Title                                                 | Description                                                                 | Key Concepts                                        |
| ------------ | ----------------------------------------------------- | --------------------------------------------------------------------------- | --------------------------------------------------- |
| **MP-01**    | [Iris Classification](coursework/machine-problem-01/) | Multi-class classification using Logistic Regression on the Iris dataset    | Supervised Learning, Classification                 |
| **MP-02**    | [Model Evaluation](coursework/machine-problem-02/)    | Comprehensive ML workflow with Logistic Regression on Breast Cancer dataset | Cross-Validation, Confusion Matrix, Learning Curves |
| **Exercise** | [California Housing](coursework/california-housing/)  | Regression analysis comparing Linear Regression and Decision Tree models    | Regression, Feature Scaling, MSE/R²                 |

---

## Technologies

### Machine Learning Stack

- **Python 3.x** — Primary programming language
- **Scikit-learn** — Machine learning algorithms and utilities
- **Pandas** — Data manipulation and analysis
- **NumPy** — Numerical computing
- **Matplotlib / Seaborn** — Data visualization

### Web Portfolio

- **HTML5 / CSS3** — Structure and styling
- **Tailwind CSS** — Utility-first CSS framework
- **JavaScript** — Interactive components

---

## Getting Started

### Prerequisites

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

### Running Notebooks

1. Clone the repository:

   ```bash
   git clone https://github.com/emperuna/CSST102-3A-AY2526.git
   cd CSST102-3A-AY2526
   ```

2. Launch Jupyter:

   ```bash
   jupyter notebook
   ```

3. Navigate to `coursework/` and open any `.ipynb` file

### Viewing the Portfolio

Open `index.html` in your browser to view the web portfolio.

---

## Project Structure

```
CSST102-3A-AY2526/
├── index.html                    # Homepage
├── about.html                    # About page
├── activities.html               # Activities listing
├── activities/                   # Activity detail pages
│   ├── mp-01.html
│   ├── mp-02.html
│   └── california-housing.html
├── coursework/                   # Source notebooks and files
│   ├── machine-problem-01/
│   │   └── machine_problem_1.ipynb
│   ├── machine-problem-02/
│   │   ├── logistic_regression.ipynb
│   │   ├── report.pdf
│   │   ├── confusion_matrix.png
│   │   └── learning_curve.png
│   └── california-housing/
│       └── california-housing.ipynb
└── assets/
    ├── css/theme.css
    ├── js/
    └── images/
```

---

## Author

<table>
  <tr>
    <td align="center">
      <strong>Jeremy M. Garin</strong><br>
      BSCS — 3A • Academic Year 2025-2026<br><br>
      <a href="https://github.com/emperuna">
        <img src="https://img.shields.io/badge/GitHub-emperuna-181717?style=for-the-badge&logo=github" alt="GitHub">
      </a>
      <a href="https://emperuna.github.io/CSST102-3A-AY2526/">
        <img src="https://img.shields.io/badge/Portfolio-Live_Demo-10b981?style=for-the-badge&logo=github-pages" alt="Portfolio">
      </a>
    </td>
  </tr>
</table>

---

## License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

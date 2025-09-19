# 🐧 Pearson’s Correlation on Penguins Dataset

## Overview

This project demonstrates the application of **Pearson’s Correlation Coefficient** on a real-world dataset.
We use the **Palmer Penguins dataset** (available via Seaborn) to explore relationships between penguin physical measurements such as **bill length, bill depth, flipper length, and body mass**.

---

## Features

* Compute Pearson’s Correlation Coefficient between two numeric variables
* Generate a correlation matrix for all numeric features
* Visualize relationships using pairplots and heatmaps
* Simple and easy-to-implement statistical analysis
* Clean, modular, and well-documented code

---

## Tech Stack

* Python 3.x
* pandas
* seaborn
* scipy
* matplotlib

---

## Installation

1. **Clone the Repository**

```bash
git clone https://github.com/your-username/penguins-correlation.git
cd penguins-correlation
```
2. **Install Dependencies**

 ```bash
pip install pandas seaborn scipy matplotlib
```

## Usage

1. **To run the correlation analysis:**

```bash
assign.ipynb
```
This will:

* Load the Palmer Penguins dataset
* Clean missing values
* Compute Pearson’s Correlation between bill_length_mm and flipper_length_mm
* Generate a correlation matrix for all four numeric features
* Display results with pairplots and a heatmap

## Output
* Correlation coefficient (e.g., ~0.87 for bill length vs flipper length)
* P-value indicating statistical significance (usually very small)
* Correlation matrix for all numeric features
* Visualizations:
  * Pairplot of numeric features
  * Heatmap showing correlation strength

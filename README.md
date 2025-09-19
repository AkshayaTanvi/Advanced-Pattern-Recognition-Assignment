# Advanced-Pattern-Recognition-Assignment

Pearson’s Correlation on Penguins Dataset

Overview

This project demonstrates how to apply Pearson’s Correlation Coefficient on a real-world dataset.
We use the Palmer Penguins dataset (available via Seaborn) to explore relationships between penguin physical measurements such as bill length, bill depth, flipper length, and body mass.

Dataset

Source: Palmer Penguins

Features used:

bill_length_mm

bill_depth_mm

flipper_length_mm

body_mass_g

Missing values were removed to ensure accurate correlation analysis.

Objective

Compute Pearson’s Correlation Coefficient between two numeric variables (e.g., bill_length_mm and flipper_length_mm).

Generate a correlation matrix for all numeric features.

Visualize the relationships using pairplots and a heatmap.

Tools & Libraries

Python 3

pandas
 – data manipulation

seaborn
 – dataset loading & visualization

scipy
 – statistical computation

matplotlib
 – plotting

Expected Output

Correlation coefficient (e.g., ~0.87 for bill length vs flipper length).

P-value indicating statistical significance (usually very small).

Correlation matrix for all four numeric features.

Visualizations:

Pairplot of numeric features.

Heatmap showing correlation strength.

How to Run

Clone this repo:

git clone https://github.com/your-username/penguins-correlation.git
cd penguins-correlation


Install required libraries:

pip install pandas seaborn scipy matplotlib


Run the script:

python correlation_penguins.py

Learn More

Pearson’s Correlation Coefficient

Palmer Penguins Dataset

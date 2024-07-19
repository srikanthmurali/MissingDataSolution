# Handling Missing Data in IoT and Manufacturing: MCAR, MAR, and MNAR

In IoT and manufacturing, understanding and addressing missing data is crucial. This project provides a clear explanation of different types of missing data—Missing Completely at Random (MCAR), Missing at Random (MAR), and Missing Not at Random (MNAR)—and demonstrates how to handle them using Python.

## Types of Missing Data

### 1. Missing Completely at Random (MCAR)
- **Definition**: Missing data is independent of any variables.
- **Example**: Random sensor failures.
- **Handling**: Enhance data capture systems at the digitization level. If MCAR occurs, use simple imputation methods.

### 2. Missing at Random (MAR)
- **Definition**: Missing data depends on observed variables.
- **Example**: Sensors in high-temperature zones fail more often.
- **Handling**: Use advanced imputation techniques like multiple imputation at the data imputation level.

### 3. Missing Not at Random (MNAR)
- **Definition**: Missing data depends on the missing values themselves or unobserved factors.
- **Example**: Machines with severe malfunctions stop reporting data.
- **Handling**: Investigate and address causes of missing data at the data management level. Use specialized imputation techniques.

## Usage

This repository contains a Python script that simulates missing data scenarios in IoT and manufacturing, and demonstrates how to handle them.

### Requirements

- Python 3.7+
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Missingno
- Scikit-learn

### Installation

Install the required packages using pip:

```bash
pip install pandas numpy seaborn matplotlib missingno scikit-learn

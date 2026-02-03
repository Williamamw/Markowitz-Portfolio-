# Markowitz Portfolio 
Third Year's group project : Implementation of Modern Portfolio Theory &amp; Efficient Frontier Analysis in Python. Applied to Bugarian Stocks (Academic) and CAC40 (Personal Extension)

## Note on Reproducibility
This project was originally developed in year 2023 as part of our academic coursework. Due to updates in dependencies, the code may require environment adjustements to run on the latest versions. The full analysis logic and source code remain available for review, and the final results can be viewed in the <rapport.pdf> file.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📖 Overview
This project implements **Modern Portfolio Theory (MPT)** to construct optimal portfolios by maximizing the Sharpe Ratio and minimizing volatility.

Originally developed as a university group project analyzing the **Bulgarian Stock Market**, I extended the codebase to analyze the **CAC 40 (French Stock Market)** to test the model's robustness on a major global index.

## 🎯 Key Features
- **Data Pipeline:** Automated data extraction and cleaning for multiple assets.
- **Mathematical Modeling:** Implementation of Harry Markowitz's mean-variance optimization.
- **Optimization:** Calculation of the **Efficient Frontier**, Tangency Portfolio (Max Sharpe), and Minimum Variance Portfolio.
- **Visualization:** Interactive plots showing the risk-return trade-off for individual assets vs. the optimized portfolio.

## 📂 Project Structure

### 1. The Core Extension: CAC 40 Analysis 🇫🇷
* **File:** `CAC40.ipynb`
* **Description:** A practical application of the model on the French benchmark index. This notebook fetches real-time/historical data for major French companies (LVMH, TotalEnergies, Sanofi, etc.) and computes the optimal asset allocation.

### 2. The Academic Foundation: Bulgarian Market 🇧🇬
* **File:** `Marché_Bulgarien.ipynb` & `rapport.pdf`
* **Description:** The original academic coursework. It analyzes a dataset of Bulgarian stocks provided by the university.
* **Theoretical Background:** The file `rapport.pdf` (in French) contains the detailed mathematical derivation of the formulas used in this project, including the matrix notation for portfolio variance and expected returns.

### 3. Quick Start Demo
* **File:** `Demo_simple.ipynb`
* **Description:** A simplified, lightweight version of the algorithm for quick testing and understanding the basic logic without heavy data dependencies.

## 🛠️ Technologies Used
* **Python**
* **Pandas / NumPy:** Data manipulation and matrix calculations.
* **SciPy:** Optimization algorithms (SLSQP) to solve for portfolio weights.
* **Matplotlib / Seaborn:** Visualization of the Efficient Frontier.

## 🚀 How to Run
Clone the repository:
   ```bash
   git clone https://github.com/Williamamw/Markowitz-Portfolio-Optimization.git
```
Authors: Ming Wei ANG & Léa Montestier

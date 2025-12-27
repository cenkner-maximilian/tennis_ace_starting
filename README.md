#🤖MACHINE LEARNING | 🎾 Tennis Winnings

## Overview
This project explores the relationship between player performance statistics and **career winnings** in professional tennis.

Using a structured data analysis workflow, the goal was to identify which match-level metrics are most strongly associated with financial success.

---

## Dataset
- **Source:** Codecademy project dataset
- **File:** `tennis_stats.csv`
- **Observations:** Professional tennis players
- **Target variable:** `Winnings`

---

## Objectives
- Explore correlations between performance metrics and winnings
- Build linear regression models to quantify these relationships
- Evaluate model performance and limitations

---

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- scikit-learn

---

## Methodology
1. Data loading and inspection  
2. Correlation analysis of numeric features  
3. Feature selection based on domain relevance  
4. Train/test split  
5. Linear regression modeling  
6. Model evaluation using R² score  
7. Visualization of predicted vs. actual winnings  

---

## Key Findings
- Certain metrics (e.g. aces and break point statistics) show a positive association with winnings
- Simple linear models capture part of the relationship but leave room for improvement
- Results highlight the importance of model assumptions and feature engineering

---

## Limitations
- Linear regression assumes linear relationships
- No feature scaling or interaction terms were used
- External factors (tournament level, era, injuries) are not included

---

## How to Run
```bash
pip install pandas numpy matplotlib scikit-learn

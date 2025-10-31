# bridge-condition-regression
Multiple linear regression analysis of Texas bridge condition data, exploring how structural, traffic, and design variables affect infrastructure performance.  # Bridge Condition Regression Analysis  This project was developed as part of the **MSc Data Science and Artificial Intelligence** Statistics module at **Queen Mary University of London**. 
---

##  Project Overview
- **Objective:** To identify the main predictors of bridge condition and assess the explanatory power of a multiple linear regression model.
- **Techniques Used:**
- Data preprocessing and encoding (dummy variables)
- Feature standardisation with `StandardScaler`
- Model fitting using `LinearRegression` from `scikit-learn`
- Model evaluation with Mean Squared Error (MSE) and R²
- Residual diagnostics and coefficient interpretation

---

##  Key Findings
- **Age** was the strongest negative predictor of bridge condition, confirming structural deterioration over time.
- **Material Type** and **Design Type** showed moderate effects, with some categories (e.g., steel structures) performing slightly worse than concrete.
- The model achieved an **R² ≈ 0.45**, indicating moderate explanatory power for real-world infrastructure data.

---

##  Repository Structure



---

##  Technologies & Libraries
- Python (Jupyter Notebook)
- pandas, numpy, matplotlib, seaborn
- scikit-learn

---

##  Visuals
Includes regression diagnostics and model performance plots:
- Residual distribution
- Residuals vs predicted values
- Predicted vs actual condition
- Coefficients by predictor

---

##  Skills Demonstrated
- Statistical modelling and interpretation
- Data cleaning and preprocessing
- Visualisation and communication of analytical results
- Use of Python and `scikit-learn` for applied data science

---

##  Author
**Blazej Olstza**
MSc Data Science and Artificial Intelligence, Queen Mary University of London
[LinkedIn](www.linkedin.com/in/blazej-olszta-a11844290) 

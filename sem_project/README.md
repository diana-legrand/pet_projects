# 📘 Interrelation Between Organizational Culture and Employee Behavior  
### A Structural Equation Modeling Approach

## 📝 Project Description

This project explores how different types of **perceived organizational culture** affect **employee engagement**, both directly and through **psychological mediators** such as attachment styles and the need for belonging.

We conducted a behavioral study using **Structural Equation Modeling (SEM)** in Python with the `semopy` package. The analysis includes:

- **Confirmatory Factor Analysis (CFA)** to validate measurement constructs  
- **Dimensionality reduction via Principal Component Analysis (PCA)**  
- **Mediation analysis** to evaluate indirect effects of organizational culture  
- **Regression modeling** to assess predictive strength and path coefficients  

The findings show that the **effect of organizational culture on engagement is indirect**, primarily mediated by **secure/avoidant attachment styles** and the **need for belonging**.

## 🔍 Key Methods

- **Survey-based data collection** (N = 142)
- **PCA** applied to four culture-type variables
- **SEM** model structure:  
  - Direct path: `culture_pca → engagement`  
  - Indirect paths through: `attachment_safe`, `attachment_avoidant`, `attachment_ambivalent`, `belongingness`, `self_definition`

## 🔧 Tools and Libraries

- `pandas` – Data manipulation  
- `semopy` – Structural equation modeling  
- `statsmodels` – Regression analysis and diagnostics  
- `scikit-learn` – PCA and preprocessing  

## 📁 Files

- `sem_project.ipynb` – Full analysis in a Jupyter Notebook  
- `README.md` – Project summary and methods overview  

## 📌 Main Conclusion

> Organizational culture influences employee engagement **indirectly** via dispositional characteristics.  
> The strongest mediators are **attachment styles** (especially avoidant and secure) and the **need for belonging**.

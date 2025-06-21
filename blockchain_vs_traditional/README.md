# Startup Success in the Digital Economy: A Comparative Research on Blockchain and Traditional IT Firms

This repository documents a research project investigating the **determinants of startup success**, with a particular focus on contrasting **blockchain startups** and **traditional technology firms**. Special attention is given to modeling **interaction effects**, revealing how the influence of key predictors varies by technological context.

[📘 View the Jupyter Notebook – blockchain_vs_traditional_valuation.ipynb](https://github.com/diana-legrand/pet_projects/blob/main/blockchain_vs_traditional/blockchain_vs_traditional_valuation.ipynb)


---

## 🎯 Research Objectives

- To identify which variables influence the probability of startup success across different technological domains.
- To evaluate the role of **non-financial indicators**—such as GitHub presence, linguistic tone, and KPI transparency—in predicting success.
- To incorporate **interaction terms** to assess whether the effect of core predictors varies significantly between blockchain and traditional startups.

---

## 🧪 Methodological Framework

The research relies on a robust econometric and machine learning framework, with a special focus on modeling **context-specific effects** through interaction terms.

### Main methods:
- **Logistic Regression with Interaction Terms**  
  - Captures conditional effects of predictors based on company type (`Type_bin`)
  - All numerical variables standardized via z-scores for interpretability

- **Random Forest Classifier**  
  - Used for non-linear modeling and variable importance ranking

- **NLP-Based Feature Engineering**  
  - `Tone_Index`: sentiment analysis from whitepapers/pitch materials  
  - `Uncertainty_Index`: measures lexical vagueness and ambiguity

- **Advanced Visualization**  
  - Interaction plots, violin plots, and decision tree visualizations via `dtreeviz`  
  - Marginal effects interpreted visually and statistically

---

## 📊 Key Variables

| Variable               | Description                                                   |
|------------------------|---------------------------------------------------------------|
| `Success`              | Binary outcome (1 = success via ICO or funding; 0 = failure)  |
| `Valuation_USD`        | Market valuation in USD                                       |
| `Tone_Index`           | Sentiment score (0–1)                                         |
| `Uncertainty_Index`    | Ambiguity score (0–1) from NLP                                |
| `Has_GitHub`           | Boolean: public repository presence                           |
| `Founders_Experience`  | Years in entrepreneurship or venture capital                  |
| `Business_Model_Clarity` | Ordinal (1–5), expert-judged clarity of business model       |
| `Team_Size`            | Number of employees                                           |

Interaction terms (e.g., `Valuation × Type_bin`) model differential effects by startup type.

---

## 📌 Key Findings: The Role of Interaction Effects

- **Valuation** is positively associated with success in both startup types, but the **marginal effect is greater** for **traditional firms**.
- **Founders’ experience** significantly increases success in **blockchain startups**, but has **limited or negative effect** in traditional ventures.
- **GitHub presence** is a critical success factor for blockchain startups, signaling openness and technical transparency; its role is negligible for traditional firms.
- **Textual tone** and **linguistic clarity** (via `Tone_Index` and `Uncertainty_Index`) are particularly powerful predictors in the blockchain context.

These results underscore the necessity of modeling **interaction terms** to avoid oversimplified, one-size-fits-all assumptions in success prediction.

---

## 📚 Data Sources

- [Crunchbase](https://www.crunchbase.com/)
- [ICObench](https://icobench.com/)
- [ICO Drops](https://icodrops.com/)
- [AngelList / Wellfound](https://wellfound.com/)
- [Kaggle Public Datasets](https://www.kaggle.com/)

All data were sourced from open, non-sensitive platforms and prepared in accordance with ethical data use standards.

---

## 🛠 Technical Environment

- Python 3.10  
- `pandas`, `scikit-learn`, `statsmodels`, `seaborn`, `matplotlib`  
- `TextBlob`, `nltk` for NLP analysis  
- `dtreeviz` for decision tree interpretation

---

## 🧠 Research Contribution

This research contributes to the fields of:

- **Entrepreneurial finance**  
- **Machine learning-based decision support**  
- **Valuation modeling in digital ecosystems**

By highlighting how **the same indicators yield different effects** depending on startup type, it calls for **context-aware evaluation frameworks** for venture analysis.

---


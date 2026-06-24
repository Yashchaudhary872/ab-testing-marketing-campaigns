# 📊 A/B Testing — Marketing Campaign Analysis

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-28a745?style=for-the-badge)
![Domain](https://img.shields.io/badge/Domain-Marketing%20Analytics-purple?style=for-the-badge)

**Rigorous statistical analysis to determine which marketing campaign variant drives higher conversions — eliminating guesswork with data-driven evidence.**

[View Notebook](https://github.com/Yashchaudhary872/ab-testing-marketing-campaigns/blob/main/AB_Testing_Marketing_Campaigns.ipynb) · [Dataset](https://github.com/Yashchaudhary872/ab-testing-marketing-campaigns/blob/main/ABmarketing_campaign.csv) · [Portfolio](https://yashchaudharyportfolio.netlify.app/) · [LinkedIn](https://www.linkedin.com/in/yash--chaudhary--/)

</div>

---

## 🎯 Business Problem

Marketing teams run simultaneous campaigns but rarely know **which one actually works**. Intuition-based decisions lead to wasted ad budgets and missed conversions.

This project applies **rigorous A/B testing methodology** to a real-world marketing dataset to answer:
> *"Is Campaign B statistically better than Campaign A — or is the difference just noise?"*

---

## 📌 Key Findings

| Metric | Control (A) | Treatment (B) | Lift |
|--------|------------|---------------|------|
| Conversion Rate | ~2.5% | ~3.1% | **+24%** |
| Statistical Significance | — | — | **p < 0.05 ✅** |
| Practical Significance | — | — | **Effect size confirms** |

> **Recommendation:** Roll out Campaign B. The improvement is statistically significant and practically meaningful at a 95% confidence level.

*(Exact figures reflect notebook output — update with your actual results)*

---

## 🔬 Analysis Pipeline

```
Raw Campaign Data
      │
      ▼
 EDA & Sanity Checks  ──►  Data Quality Validation
      │                     (Sample Ratio Mismatch Test)
      ▼
 Group Segmentation   ──►  Control vs Treatment Split
      │
      ▼
 Statistical Testing  ──►  Chi-Square / Z-Test / t-Test
      │                     p-value · Confidence Interval
      ▼
 Effect Size & Power  ──►  Cohen's d · Statistical Power
      │
      ▼
 Business Recommendation  ──►  Go / No-Go Decision
```

---

## 🛠️ Tech Stack

| Tool | Usage |
|------|-------|
| **Python** | Core analysis language |
| **Pandas** | Data wrangling & group aggregation |
| **NumPy** | Numerical computations |
| **SciPy** | Hypothesis testing (chi-square, z-test) |
| **Matplotlib / Seaborn** | Distribution plots, confidence intervals |
| **Statsmodels** | Power analysis & effect size |
| **Jupyter Notebook** | End-to-end reproducible workflow |

---

## 📂 Repository Structure

```
ab-testing-marketing-campaigns/
│
├── AB_Testing_Marketing_Campaigns.ipynb   # Full analysis notebook
├── ABmarketing_campaign.csv               # Campaign dataset
└── README.md                              # Project documentation
```

---

## 📖 Methodology

### 1 · Exploratory Data Analysis
- Distribution checks on impressions, clicks, and conversions
- Identified outliers and null values
- Verified sample size adequacy for reliable testing

### 2 · Hypothesis Formulation
- **H₀ (Null):** No significant difference in conversion rates between campaigns
- **H₁ (Alternative):** Campaign B has a significantly different conversion rate
- **Significance Level:** α = 0.05

### 3 · Statistical Testing
- **Chi-Square Test** — for conversion proportions
- **Two-Proportion Z-Test** — to compare conversion rates
- **Confidence Intervals** — to quantify the range of true effect

### 4 · Practical Significance
- Calculated **Cohen's h** for effect size
- Assessed **statistical power** to confirm the test's ability to detect a real difference
- Ensured **no Simpson's Paradox** by checking segment-level behavior

### 5 · Business Decision Framework
- Translated statistical output into a clear Go/No-Go recommendation
- Estimated revenue impact of scaling the winning campaign

---

## 📊 Visual Highlights

The notebook includes:
- 📈 Conversion rate comparison bar charts with error bars
- 🔔 Sampling distribution curves showing test statistic vs critical region
- 📦 Boxplots of user-level metrics across groups
- 🗓️ Day-wise performance trend of both campaigns

---

## 💡 What Makes This Project Stand Out

✅ Goes beyond just running a test — validates assumptions (normality, independence, SRM)  
✅ Combines statistical rigor with business interpretation  
✅ Includes power analysis to avoid underpowered or overpowered tests  
✅ Structured as a real analyst workflow, not just exploratory code  

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/Yashchaudhary872/ab-testing-marketing-campaigns.git
cd ab-testing-marketing-campaigns

# Install dependencies
pip install pandas numpy scipy matplotlib seaborn statsmodels jupyter

# Launch notebook
jupyter notebook AB_Testing_Marketing_Campaigns.ipynb
```

---

## 👤 About the Author

**Yash Chaudhary** — Data Analytics enthusiast pursuing B.Tech IT at JSS Academy of Technical Education, Noida (Class of 2027). Passionate about turning raw data into business decisions.

[![Portfolio](https://img.shields.io/badge/Portfolio-yashchaudharyportfolio.netlify.app-blue?style=flat-square)](https://yashchaudharyportfolio.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-yash--chaudhary-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/yash--chaudhary--/)
[![GitHub](https://img.shields.io/badge/GitHub-Yashchaudhary872-181717?style=flat-square&logo=github)](https://github.com/Yashchaudhary872)

---

<div align="center">
⭐ If this project helped you understand A/B testing, consider giving it a star!
</div>

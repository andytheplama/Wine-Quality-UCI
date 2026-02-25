# 🍷 Wine Quality Analysis

An exploratory data analysis project investigating the chemical properties that influence wine quality ratings, using the UCI Wine Quality dataset.

---

## 📌 Hypothesis

> **Alcohol and sulphates positively correlate with wine quality, while volatile acidity negatively correlates with wine quality.**

---

## 📁 Dataset

- **Source:** [UCI Machine Learning Repository – Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/wine+quality)
- **Files:** `winequality-red.csv`, `winequality-white.csv`
- **Size:** 6,497 total samples (1,599 red · 4,898 white)
- **Target variable:** `quality` (score from 0–10 based on sensory evaluation)
- **Features:** 11 physicochemical properties including alcohol, sulphates, volatile acidity, pH, residual sugar, and more

---

## 🔧 Tools & Libraries

| Tool | Purpose |
|------|---------|
| Python | Core language |
| Pandas | Data loading and manipulation |
| Matplotlib | Plotting |
| Seaborn | Statistical visualizations |

---

## 📊 Key Findings

| Feature | Correlation with Quality |
|---------|------------------------|
| Alcohol | **+0.44** (strongest positive predictor) |
| Sulphates | +0.04 |
| Volatile Acidity | **-0.27** (strongest negative predictor) |

- **Alcohol** showed the clearest upward trend — higher-quality wines consistently had higher alcohol content
- **Volatile acidity** (acetic acid) negatively impacted quality, likely due to its vinegar-like taste at high concentrations
- **Sulphates** had a weaker but still positive relationship with quality

The hypothesis was **supported**: alcohol and volatile acidity were the most impactful predictors, while sulphates showed only a modest effect.

---

## 📈 Visualizations

- Correlation heatmap across key features
- Box plots of alcohol, sulphates, and volatile acidity by quality score
- Regression plots showing trend lines for each feature vs. quality

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/andytheplama/Wine-Quality-UCI.git
cd Wine-Quality-UCI

# Install dependencies
pip install pandas matplotlib seaborn

# Launch the notebook
jupyter notebook Andy-TheplamaWine_quality_.ipynb
```

---

## 📂 Repository Structure

```
Wine-Quality-UCI/
├── winequality-red.csv
├── winequality-white.csv
├── winequality.names
├── Andy-TheplamaWine_quality_.ipynb
├── alcohol_vs_quality.png
├── sulphates_vs_quality.png
├── volatile_acidity_vs_quality.png
└── README.md
```

---

## 👤 Author

**Andy Theplama**  
University of Arkansas — Data Science & Accounting  
[LinkedIn](https://www.linkedin.com/in/andy-theplama) · [GitHub](https://github.com/andytheplama)

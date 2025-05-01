# 🏃 Boston Marathon 2023: Bib Number and Performance

This project analyzes runner performance in the 2023 Boston Marathon using public race data.  
We examine how bib numbers — assigned based on qualifying times — relate to actual finish performance,  
with further analysis by gender and age group.

---

## 📈 Project Overview

- **Motivation**: Can bib numbers predict actual race performance?
- **Key Questions**:
  - Does a lower bib number lead to faster finish times?
  - Are there performance differences by gender or age?

---

## 📊 Data Source

The dataset was retrieved from the Score Network:

🔗 https://data.scorenetwork.org/running/boston_marathon_2023.html

- 26,000+ runners
- Variables used: `bib_number`, `finish_net_minutes`, `gender`, `age_group`

---

## 🔍 Analysis Summary

- **Bib Number vs Finish Time**: Strong positive relationship (OLS R² = 0.61)
- **Gender Comparison**: Women finish ~23.5 minutes slower on average (t-test p < 0.001)
- **Age Trends**: Average finish time increases steadily with age

Visualizations include:
- Scatter plots with regression lines
- Violin plots by gender
- Age group bar charts
- Density plots for distribution comparisons

---

## 📂 Files

| File | Description |
|------|-------------|
| `index.html` | Final HTML slide deck (open with GitHub Pages) |
| `Boston_Marathon_Final_Slides.Rmd` | Source R Markdown for the presentation |
| `boston_marathon_2023_cleaned.csv` | Cleaned dataset used in analysis |
| `fonts.html`, `.css` | Custom styling and font settings |

---

## 🌐 View the Slides

🔗 [View the presentation](https://bk4098a.github.io/boston-marathon-presentation/)

---

## 👩‍💻 Author

Byeolha Kim  
Master's Student, American University  
](https://github.com/bk4098a/boston-marathon-presentation)

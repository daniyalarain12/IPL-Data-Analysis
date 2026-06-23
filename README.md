# 🏏 IPL Data Analysis — Indian Premier League Complete EDA

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.x-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-1.x-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-orange?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-0.13.x-4C72B0?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

> A complete Exploratory Data Analysis on 1,243 IPL matches spanning all seasons from 2008 to 2026 — uncovering team dominance, toss impact, title history, biggest victories, venue statistics and Player of the Match records using Python, Pandas, Matplotlib and Seaborn.

---

## 📁 Repository Structure

```
IPL-Data-Analysis/
│
├── IPL_Complete_Analysis.ipynb
├── ipl.csv
└── README.md
```

---

## 📂 Dataset

| Detail | Info |
|--------|------|
| **File** | ipl.csv |
| **Source** | [Kaggle — IPL Comprehensive Dataset](https://www.kaggle.com) |
| **Rows** | 1,243 matches |
| **Seasons** | 2008 – 2026 (Complete IPL History) |
| **Content** | Match-level data — teams, toss, venue, result, win margin, player of the match |
| **Teams** | All 19 franchises ever in IPL history |

---

## 🧹 Data Cleaning

| Step | Action |
|------|--------|
| Dropped column | `match_number` — 74 missing values, not needed for analysis |
| Standardized team names | Replaced old franchise names with current names |
| Converted date | `date` column converted from string to datetime format |
| Extracted season | Year extracted from `date` column into `season` column |
| New column | `toss_match_winner` — YES/NO column using NumPy `np.where()` |

### Team Name Standardization
| Old Name | New Name |
|----------|----------|
| Delhi Daredevils | Delhi Capitals |
| Kings XI Punjab | Punjab Kings |
| Royal Challengers Bangalore | Royal Challengers Bengaluru |
| Rising Pune Supergiant | Rising Pune Supergiants |

---

## 📊 Analyses Performed

| # | Analysis | Chart Type | Key Question |
|---|----------|------------|-------------|
| 01 | Most Successful Teams | Horizontal Bar | Which teams have won the most IPL matches? |
| 02 | IPL Season Growth | Line Plot | How has IPL expanded season by season? |
| 03 | Toss Decision Distribution | Bar + Line (Subplots) | Do captains prefer bat or field — and has it changed? |
| 04 | Toss Winner vs Match Winner | Pie Chart | Does winning the toss help you win the match? |
| 05 | Top 10 POTM Winners | Horizontal Bar | Which players dominated the Player of the Match award? |
| 06 | Most Matches Hosted | Horizontal Bar | Which stadiums are the heartbeat of IPL? |
| 07 | Biggest Wins by Runs | Horizontal Bar | Which were the most one-sided run victories? |
| 08 | Teams with Most 10-Wicket Wins | Horizontal Bar | Which teams are most dominant by wickets? |
| 09 | Team Win Percentage | Horizontal Bar | Which teams are most consistently dominant? |
| 10 | IPL Title Winners | Horizontal Bar | Which franchises have won the most IPL trophies? |
| 11 | Final Dashboard | 6-Chart Subplots | Complete IPL Analysis at a glance |

---

## 🔑 Key Insights

- **Mumbai Indians** dominate both total wins and win percentage across IPL history
- **AB de Villiers** leads the Player of the Match tally — the most impactful player in IPL history
- Teams increasingly prefer **fielding first** after winning the toss in recent seasons
- Winning the toss does **not guarantee** winning the match — data proves it
- **Eden Gardens** and **Wankhede Stadium** are the most iconic IPL venues
- **Chennai Super Kings** and **Mumbai Indians** are the most successful franchises in terms of IPL titles

---

## 🛠️ Tech Stack

| Library | Purpose |
|---------|---------|
| **Pandas** | Data loading, cleaning, filtering, groupby and aggregation |
| **NumPy** | Numerical operations and conditional column creation with `np.where()` |
| **Matplotlib** | Core visualizations — bar, line, pie charts and subplots dashboard |
| **Seaborn** | Statistical line plots for trend analysis |

---

## ▶️ How to Run

1. Clone the repository
```bash
git clone https://github.com/daniyalarain12/IPL-Data-Analysis.git
```

2. Install required libraries
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Launch Jupyter Notebook
```bash
jupyter notebook
```

4. Open `IPL_Complete_Analysis.ipynb` and run all cells

---

## 🗺️ My Data Science Learning Journey

This project is part of my ongoing Data Science & AI Engineering roadmap:

| Repository | Status |
|-----------|--------|
| [Python — Basics to Advanced](https://github.com/daniyalarain12/Python-Basics-to-Advanced) | ✅ Completed |
| [NumPy — Basics to Advanced](https://github.com/daniyalarain12/NumPy-Basics-To-Advanced) | ✅ Completed |
| [Pandas — Basics to Advanced](https://github.com/daniyalarain12/Pandas-Basics-to-Advanced) | ✅ Completed |
| [Matplotlib — Basics to Advanced](https://github.com/daniyalarain12/Matplotlib-Basics-to-Advanced) | ✅ Completed |
| [Netflix EDA — Project](https://github.com/daniyalarain12/Netflix-EDA-Visualization) | ✅ Completed |
| [Seaborn — Basics to Advanced](https://github.com/daniyalarain12/Seaborn-Basics-to-Advanced) | ✅ Completed |
| **IPL Data Analysis — Project** | ✅ Completed |
| More EDA Projects | 🔜 Coming Soon |
| Machine Learning | 🔜 Coming Soon |

---

## 📬 Connect With Me

[![GitHub](https://img.shields.io/badge/GitHub-daniyalarain12-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/daniyalarain12)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/daniyal-arain)

---

⭐ **If you find this repository helpful, please give it a star!** ⭐

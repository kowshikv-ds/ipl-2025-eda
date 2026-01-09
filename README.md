# IPL 2025 Exploratory Data Analysis

## Overview
This project presents an exploratory data analysis (EDA) of the IPL 2025 season, focusing on both individual and team-level performance using batting and bowling statistics. The analysis was carried out to regain hands-on coding practice while applying structured analytical thinking to a real-world sports dataset.

Rather than relying on raw aggregates, the project emphasizes fair comparisons, weighted metrics, and clear visualizations to derive meaningful insights.

---

## Objectives
- Analyze individual batting and bowling performances in IPL 2025  
- Compare top performers against season-wide averages  
- Evaluate team-level batting and bowling efficiency using weighted metrics  
- Study the balance between batting and bowling efficiency across teams  

---

## Questions Explored
1. Which batsman scored the highest runs in the season, and how does his performance compare to an average batsman?
2. Which bowler took the most wickets, and how does his performance compare to an average bowler?
3. Which teams have the most efficient batters based on weighted strike rate?
4. Which teams have the most economical bowlers based on weighted economy rate?
5. How do teams compare when batting and bowling efficiency are analyzed together?

---

## Dataset
- Source: Kaggle (IPL 2025 dataset)
- Data includes player-level batting and bowling statistics for the IPL 2025 season.
- The dataset is not uploaded to this repository due to licensing considerations.  
  Please refer to the Kaggle link to access the data.

---

## Methodology
- Data cleaning and type conversion were performed to ensure consistency.
- Qualification thresholds were applied to avoid small-sample bias:
  - Batting analysis: minimum balls faced
  - Bowling analysis: minimum overs bowled
- Team-level efficiency metrics were computed using aggregate-first approaches:
  - Weighted Strike Rate for batting efficiency
  - Weighted Economy Rate for bowling efficiency
- Visualizations were used to support comparisons and insights.

---

## Key Insights
- Top individual performers significantly outperform season-wide averages across key metrics.
- Team batting and bowling efficiencies show clear variation when weighted metrics are applied.
- No single team dominates both batting and bowling efficiency, indicating a trade-off between the two across teams.
- Combined efficiency analysis highlights distinct team strengths and weaknesses.

---

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Conclusion
This project reinforced the importance of thinking before coding, defining fair metrics, and avoiding misleading averages in data analysis. It served as a practical exercise to regain analytical momentum while building an end-to-end EDA workflow on a real-world dataset.

---

## Future Scope
- Extend the analysis to match-level or phase-wise performance
- Compare IPL 2025 trends with previous seasons
- Incorporate interactive visualizations or dashboards

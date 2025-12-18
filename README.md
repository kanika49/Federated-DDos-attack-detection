# A/B Testing for Product Feature Impact Analysis

## Project Overview
This project evaluates the impact of a new product feature on user engagement using A/B Testing and statistical hypothesis testing.  
The goal is to determine whether the feature leads to a statistically significant improvement in Click Through Rate (CTR) and to support data-driven product decisions.

This project demonstrates an end-to-end Data Science workflow including data simulation, analysis, visualization, statistical testing, and business insight generation.

---

## Objective
- Compare user engagement between Control (A) and Test (B) groups
- Measure the impact of a new product feature using CTR
- Validate results using statistical significance testing
- Provide actionable insights for product rollout decisions

---

## Dataset
The dataset is synthetically generated to simulate real-world product usage behavior.

Total users: 15,000

### Features
- user_id: Unique user identifier
- group: Control (A) or Test (B)
- device: Mobile or Desktop
- country: USA, India, UK, Germany
- clicked: 1 = Clicked, 0 = Not Clicked

---

## Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Statsmodels
- Jupyter Notebook
- Git, GitHub

---

## Methodology
1. Simulated realistic user interaction data
2. Calculated CTR for control and test groups
3. Visualized CTR comparison using bar plots
4. Performed Z-test for proportions to test statistical significance
5. Conducted segmentation analysis by device type and country
6. Interpreted results to generate business insights

---

## Results & Insights
- Test group (B) showed a higher CTR compared to control group (A)
- Statistical testing confirmed the difference was significant (p < 0.05)
- Mobile users demonstrated higher engagement than Desktop users
- Certain regions showed stronger feature adoption

Business Insight:
The feature can be rolled out incrementally, prioritizing high-performing user segments such as Mobile users and high-engagement regions.

---

## How to Run
```bash
git clone https://github.com/kanika49/Federated-DDos-attack-detection


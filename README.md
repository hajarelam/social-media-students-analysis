# Social Media & Student Well-being — EDA

## Objective
Explore relationships between social media usage and:
- Academic performance impact
- Mental health score
- Sleep hours
- Social media conflicts
- Addiction score

## Dataset
`Students Social Media Addiction.csv` (delimiter `;`).

## Key Insights
- Addiction score is strongly correlated with conflicts over social media.
- Addiction score has a strong negative association with mental health.
- Students who report academic impact tend to have higher daily usage hours.
- Sleep hours decrease as addiction increases.

> Note: Correlation does not imply causation.

## Visualizations
### Gender Distribution
![Gender](images/gender_distribution.png)

### Correlation Heatmap
![Correlation](images/corr_heatmap.png)

### Addiction vs Mental Health
![Addiction vs MH](images/addiction_vs_mental_health.png)

### Platform by Country (Top 6)
![Platform by country](images/platform_by_country.png)

## Notebook
The full analysis is available here:
- `notebook/Social_Media_Student_EDA.ipynb`

## How to run
```bash
pip install -r requirements.txt

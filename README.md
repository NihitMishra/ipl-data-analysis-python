# IPL Data Analysis — Python

## Project Overview
This project explores Indian Premier League (IPL) match and ball-by-ball delivery data using Python and Pandas. It analyzes team scoring, player performance, toss decisions, and match outcomes, supported by data visualizations.

## Objectives
- Inspect dataset structure and data quality.
- Analyze team-wise and year-wise total runs.
- Identify leading run-scorers and bowlers by recorded dismissals.
- Examine toss decisions and their relationship with match outcomes.
- Summarize findings and identify limitations in the analysis.

## Tools & Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook

## Dataset Overview
- **Matches:** 1,169
- **Ball-by-ball records:** 278,205
- **Match table columns:** 28
- **Original delivery table columns:** 20

The dataset contains match details, teams, toss decisions, player information, delivery-level runs, extras, and dismissal records.

## Key Findings

### 1. Team Scoring
Mumbai Indians recorded the highest cumulative team total in the current analysis, with 45,088 runs. These raw totals are not adjusted for matches played or changes in franchise names.

### 2. Year-wise Scoring
2025 had the highest calendar-year total in the analysis, with 26,527 runs. These totals depend on the number of matches played and should not be interpreted as scoring rates per match.

### 3. Leading Run-scorers
V Kohli ranked first with 8,671 runs, followed by RG Sharma with 7,048 runs in the dataset.

### 4. Bowling Dismissals
YS Chahal ranked first in the current recorded-dismissal count, with 229. This count includes dismissals that may not be credited to the bowler.

### 5. Toss Decisions
Teams chose to field after winning the toss in 764 matches (65.4%), compared with 405 decisions to bat first (34.6%).

### 6. Toss and Match Outcomes
Among the 1,146 matches with recorded winners, the toss winner also won 591 matches, approximately 51.6%. This association does not establish causation.

## Data Quality Notes
- The match dataset contains 23 missing values in the winner column.
- Three duplicate delivery rows were identified and should be investigated.
- The notebook should be checked for unintended columns before its results are treated as final.

## Conclusion
The analysis explores IPL scoring trends, player records, team totals, toss decisions, and match outcomes. It also highlights data-quality considerations and limitations that matter when interpreting cumulative statistics.

## Project File
- `IPL-data-analysis.ipynb` — Notebook containing the analysis and visualizations.

## Author
**Nihit Mishra**

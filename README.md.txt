# Global Freelancer Data Analysis

## Overview
Exploratory data analysis of 1000 freelancers across 
21 countries. The goal was to identify what factors 
drive hourly rates among freelancers.

## Questions Answered
1. Which skills command the highest hourly rates?
2. Does experience affect hourly rate?
3. Is there a gender pay gap?
4. Which countries have the highest paying freelancers?
5. What factors correlate with higher ratings?

## Key Findings
1. Dataset appears synthetic — only 6 fixed hourly 
   rates exist ($20, $30, $40, $50, $75, $100)
2. Country shows the strongest variation in hourly 
   rate — India highest ($57.5), Spain lowest ($43.2)
3. Skill, experience, rating and satisfaction have 
   no meaningful effect on hourly rate
4. 14.5% of freelancers had 0 rating — treated as 
   missing data not a real rating
5. Age and experience are the only strongly 
   correlated columns (r = 0.624)

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn

## Project Structure
freelancer_analysis/
├── data/
│   └── global_freelancers_raw.csv
├── freelancer_analysis.ipynb
└── README.md
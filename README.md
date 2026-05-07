# Instagram Influencer Analysis Project

## Overview
This project analyzes data from top global Instagram influencers to identify trends in follower counts, engagement rates, and overall influence scores. The goal is to provide a preprocessed dataset that can be visualized in Tableau for insightful dashboards.

## Project Structure
```
project_01_instagram_influencer_analysis/
├── README.md
├── notebooks/
│   └── instagram_influencer_preprocessing_eda.ipynb  # Data cleaning and EDA
├── data/
│   └── processed/
│       └── insta_influencers_tableau_ready.csv       # Final data for Tableau
├── dashboard/
│   └── tableau_public_link.md                        # Link to Tableau Public
└── assets/
    └── dashboard_thumbnail.png                       # Screenshot of the dashboard
```

## Data
The dataset `insta_influencers_tableau_ready.csv` contains information about influencers, including:
- **Rank & Name**: Influencer ranking and channel name
- **Followers & Likes**: Follower count, average likes, total likes
- **Engagement Rates**: Recent engagement rates (60 days)
- **Scores**: Computed influence scores and categories (e.g., Q4 High Followers)

## Next Steps
- Open the `.ipynb` file to view the data analysis process.
- Connect the `.csv` file to Tableau to build your dashboard.
- Save a screenshot of the dashboard in `assets/` and update `tableau_public_link.md`.

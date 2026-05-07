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

## Tableau Dashboard

<div class='tableauPlaceholder' id='viz1778127661549' style='position: relative'><noscript><a href='#'><img alt='인스타_인플루언서_분석_2 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;__&#47;__2_17781238341590&#47;___2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='__2_17781238341590&#47;___2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;__&#47;__2_17781238341590&#47;___2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='ko-KR' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1778127661549');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='1300px';vizElement.style.height='927px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

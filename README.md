📊 YouTube Trending Data Insights (UK)
🧠 Overview

This project analyses the YouTube Trending Videos dataset (UK subset) to uncover what drives video popularity and viewer engagement.
The analysis was performed using Python (pandas, matplotlib, seaborn) with a focus on data cleaning, feature engineering, exploratory analysis, and storytelling.

🎯 Objectives

Explore engagement behaviour and view patterns across content categories.

Engineer new metrics such as engagement rate and days to trend to quantify popularity.

Identify which types of content trend faster and attract more audience interaction.

Present insights in a clear, visual, and data-driven narrative.

🧰 Tools & Libraries

Python – Core analysis

pandas / numpy – Data wrangling and feature creation

matplotlib / seaborn – Data visualisation

Jupyter Notebook – Exploratory and reproducible analysis environment

🧹 Data Preparation

Imported the Kaggle YouTube Trending Dataset (UK).

Cleaned and formatted columns (publish_time, views, likes, comments).

Removed duplicates and handled missing values.

Engineered custom metrics:

engagement_rate = (likes + comments) / views

days_to_trend = trending_date – publish_time

📈 Key Analyses

Engagement Analysis – Compared likes, views, and comments across categories.

Trending Dynamics – Measured how quickly each category reached the trending list.

Correlation Study – Analysed relationships between engagement metrics.

Category Insights – Interpreted results in the context of viewing behaviour and popular trends.

💡 Key Insights

Music and Entertainment categories showed the highest engagement (~7%) and trended the fastest.

News and Politics trended more slowly but sustained engagement longer.

Findings align with Ofcom’s media consumption reports and illustrate the influence of culture (e.g., K-pop) on UK trending behaviour.

🚀 Results

Delivered a Jupyter Notebook showcasing data cleaning, visualisation, and insight storytelling.

Demonstrated the ability to convert unstructured data into actionable insights through analysis and visual presentation.

🔗 Dataset

Kaggle – Trending YouTube Video Statistics

🧩 Next Steps

Expand analysis to multiple countries for comparative insights.

Build an interactive dashboard using Streamlit or Plotly Dash.

Apply basic NLP to analyse comment sentiment and title keywords.

🎬 Netflix Movies & TV Shows Data Analysis
📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on the Netflix Movies and TV Shows dataset (~8,800 titles).

The goal is to uncover insights about Netflix’s catalog:

Distribution of Movies vs. TV Shows

Content growth trends over time

Most prolific countries, genres, and directors

Audience ratings breakdown

Duration analysis (movie runtimes & number of TV show seasons)

This project is part of my Data Science portfolio.

🗂 Dataset Details
Source: Kaggle – Netflix Movies and TV Shows Dataset

Rows: ~8,800

Columns: title, director, cast, country, date_added, release_year, rating, duration, listed_in, description, type

🔧 Data Cleaning
Duplicates removed.

Missing values handled (e.g., Unknown for director/country, Not Rated for rating).

Dropped rows missing date_added (needed for trend analysis).

Converted date_added to datetime, extracted year/month.

Converted duration into numeric minutes (for movies) and seasons (for TV).

📊 Analysis & Visuals
Movies vs TV Shows Count → Netflix has significantly more movies than TV shows.

Top Countries → The USA dominates, followed by India and the UK.

Content Over Time → Rapid growth from 2015 to 2020.

Top Genres → Drama, Comedies, and Documentaries dominate.

Ratings Distribution → Mature audiences (TV-MA, TV-14) are the main target.

Top Directors → Several prolific contributors, though most content is varied.

Duration Analysis

Most movies are 90–120 minutes long.

TV Shows are usually 1–2 seasons (limited series are common).

Boxplot shows movie durations trending slightly shorter in recent years.

📂 Project Structure
text
Netflix-Analysis/
│── netflix_analysis.ipynb   # Jupyter Notebook (EDA + visuals + insights)
│── README.md                 # Project documentation
│── images/                   # Optional folder for saved plot images
🛠 Tools & Libraries Used
Python (Jupyter Notebook)

pandas (data cleaning & manipulation)

matplotlib & seaborn (visualization)

📌 Key Insights (TL;DR)
Netflix content: ~2/3 Movies, ~1/3 TV Shows.

USA, India, UK are the top content creators.

Strong growth in content post‑2015, peak around 2017‑2020.

Drama & Comedy are the most common genres.

Audience skew favors mature ratings (TV-MA, TV-14).

Movie durations: most between 90–120 minutes.

TV shows: majority have only 1 season.

🚀 How to Run
Clone this repo or download as ZIP.

Download the dataset from Kaggle: Netflix Movies and TV Shows.

Place netflix_titles.csv in the project folder.

Run in Jupyter Notebook:

bash
jupyter notebook netflix_analysis.ipynb
🔮 Future Improvements
Perform advanced NLP on descriptions to identify hidden themes.

Build a better visualization dashboard (using Plotly or Tableau).

Compare Netflix dataset with competitors (Prime, Disney+) for market insights.

🤝 Acknowledgements
Dataset: Kaggle Community Dataset

Analysis prepared by Ishan ✨

✅ This README is compact but story-driven:

Starts with an overview.

Walks through data, cleaning, analysis steps.

Ends with insights + future improvements.

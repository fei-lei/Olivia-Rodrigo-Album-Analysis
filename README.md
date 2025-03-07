🎶 Olivia Rodrigo Album Analysis

📌 Project Overview

This project explores Olivia Rodrigo’s discography by analyzing song lyrics, sentiment trends, and streaming statistics across her albums. Using Python, NLP, and Tableau, I extracted and cleaned metadata from the Spotify API, integrated it with lyrics, and applied sentiment analysis and topic modeling to uncover recurring themes in her music.

📂 Dataset Creation & Cleaning

1️⃣ Extracting Album & Track Data
I used the Spotify Web API to retrieve:

Track metadata (track name, album, release date)

2️⃣ Merging Lyrics with Spotify Data
Since Spotify doesn’t provide lyrics, I used lyrics data from Kaggle and merged them with the track data.
To handle inconsistencies in track names, I have to rename some of the track name from the Kaggle data set before merge the data together.

📝 Sentiment Analysis & Topic Modeling

Sentiment Analysis
I applied NLP techniques to analyze lyrical sentiment:

Used NLTK’s VADER Sentiment Analyzer to classify lyrics as positive, neutral, or negative.
Aggregated sentiment scores at the album level to observe emotional shifts across her discography.

Topic Modeling (BERTopic)
To discover recurring themes, I leveraged BERTopic, a transformer-based clustering model:

Extracted key topics from lyrics.
Created visualizations of thematic distributions across albums.
📊 Interactive Dashboard (Tableau)

To make the insights more accessible, I built an interactive Tableau dashboard that visualizes:

🎭 Sentiment Trends: How lyrical sentiment changes across albums.
📈 Streaming Popularity: Comparing track sentiment to popularity scores.
📌 Lyrical Themes: Interactive topic clusters showing dominant themes in her songs.
🔧 Tools & Libraries

Data Extraction: Spotify API (spotipy), requests
Data Cleaning & Processing: pandas, numpy
Natural Language Processing: nltk, BERTopic
Visualization: Tableau

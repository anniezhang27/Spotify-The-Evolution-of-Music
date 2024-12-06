# Spotify-The-Evolution-of-Music

# **Spotify: The Evolution of Music**  
*Exploratory Data Science Project – DSC Expo 2023*

---

## **Abstract**  
It is challenging to quantify the evolution of music over time. While concepts like "vibes" and "moods" have been used to describe trends in music, there is little quantitative analysis to support these descriptions. This project analyzes over 10,000 songs on Spotify and their musical features, utilizing time-series analysis and predictive modeling to forecast future trends. Our goal is to help both artists and listeners understand the direction of music and streaming through data-driven insights.  

---

## **Tools and Libraries Used**  
- **Programming Languages**: Python  
- **Libraries**:  
  - Pandas  
  - NumPy  
  - Matplotlib & Seaborn  
  - Scikit-learn  
  - Plotly  

---

## **Datasets**  
- **Source**: Spotify API and Kaggle  
  - [Spotify Dataset (1986-2023)](https://www.kaggle.com/datasets/nicolasfierro/spotify-1986-2023)  
- **Size**: 10,000+ songs  
- **Features**:  
  - Objective: Key, genre, release date  
  - Subjective: Danceability, valence, energy  

---

## **Project Outline**  
1. **Introduction**: Understanding the challenges of quantifying musical trends.  
2. **Data Loading and Preprocessing**:  
   - Transforming raw data into usable formats.  
   - Addressing errors and inconsistencies in the dataset.  
3. **Exploratory Data Analysis (EDA)**:  
   - Analyzing distributions, relationships, and patterns in features such as danceability, energy, and loudness.  
   - Visualizing trends over time.  
4. **Data Processing and Predictive Modeling**:  
   - Building and testing models to predict the prevalence of specific musical features in future music.  
   - Techniques used: Time-series analysis, clustering, and regression.  
5. **Conclusion**: Insights into where music trends and streaming are headed.  

---

## **Domain Knowledge**  
The dataset included various musical features analyzed to understand trends:  

- **Popularity**: Score (0-100) derived from audience reception.  
- **Danceability**: How suitable a track is for dancing based on tempo and rhythm stability.  
- **Energy**: Perceived intensity and activity of a track.  
- **Valence**: Emotional positivity conveyed by the music.  
- **Tempo**: Beats per minute (BPM).  
- **Loudness, Instrumentalness, Acousticness**: Key indicators of a track’s auditory characteristics.  

For a full list of features and descriptions, refer to the [project documentation](#).  

---

## **Key Findings**  
- **Trends Over Time**:  
  - Observed shifts in musical preferences, such as increased energy and faster tempos in popular tracks.  
  - Decline in acoustic and instrumental tracks, highlighting evolving listener preferences.  
- **Genre Insights**:  
  - Certain genres, such as pop and hip-hop, show strong correlations with features like danceability and energy.  
- **Model Performance**:  
  - Time-series models effectively forecasted feature trends, providing actionable insights into music evolution.  

---

## **Visualizations**  
- **Feature Correlation Heatmap**: Analyzed relationships between features like valence, tempo, and popularity.  
- **Time-Series Analysis**: Mapped changes in danceability, energy, and loudness over decades.  
- **Clustered Trends**: Grouped similar tracks to identify patterns in genres and listener preferences.  

---

## **Conclusion and Future Directions**  
- **Insights**:  
  - Quantitative analysis of musical features provides a clearer understanding of music trends.  
  - Artists and producers can use these insights to align with audience preferences.  
- **Future Work**:  
  - Integrate external datasets, such as social media trends or streaming metrics, for a more holistic view.  
  - Expand predictive modeling to include additional features like lyrics sentiment analysis.  

---

## **Acknowledgments**  
Special thanks to my teammate, Krystal Wu, and the **DSC Expo 2023** organizers and the Kaggle community for providing the dataset.  

---

Feel free to use or adapt this README for your GitHub repository. Let me know if you’d like further refinements! 😊

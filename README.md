# Music Artist & Song Popularity Analysis

## Project Objective

The goal of this analysis is to help a music agency identify:
- Which artists are worth collaborating with based on popularity trends?
- Which song features or genres to focus on to maximize the chances of success?
- Insights to guide artist and track selection strategies?

## Data Sources
 
  Dataset used for analysis: [Spotify Huge Database - Daily Charts Over 3 Years](https://www.kaggle.com/datasets/pepepython/spotify-huge-database-daily-charts-over-3-years) from Kaggle.

## Analysis Highlights

1. **Artist Popularity Trends**  
   Identified top artists who maintain or grow their popularity over time.  
   *Recommendation:* Focus on artists with stable or rising popularity.

2. **Song Popularity Distribution**  
   Most songs have popularity below 20,000, with a few outliers deserving closer examination.

3. **Popularity by Release Month**  
   Songs released in summer and winter months tend to have higher popularity, possibly due to festivals and holidays.

4. **Followers vs Popularity**  
   No significant correlation was found between the number of artist followers and the popularity of their songs. Followers' count has minimal impact on collaboration choices.

5. **Song Features Impact**  
   - *Valence* (musical positivity) shows no strong correlation with popularity.  
   - *Explicit* songs tend to be less popular than non-explicit ones; focusing on non-explicit content might be advantageous.

6. **Genre Insights**  
   Top genres by median popularity include Sad Rap, Turkish Trap, and Nuevo Regional Mexicano.  
   Pop has the highest number of popular songs, making it a strategic genre to focus on.

7. **Top Global Artists**  
   Agencies should consider collaborating with the most popular global artists or promising ones within similar genres.

## Tools Used

- Python (Pandas, Matplotlib, Seaborn, SciPy)
- Jupyter Notebook for analysis and visualization

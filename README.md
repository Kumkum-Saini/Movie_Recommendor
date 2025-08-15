# 🎬 Movie Recommendation System with Sentiment Analysis

This project is a **content-based movie recommendation system** that suggests the top 10 movies similar to a given favorite movie.  
It uses **cosine similarity** on movie metadata (genre, keywords, overview, tagline, etc.) and enhances the recommendations with **sentiment analysis** on the movie descriptions.

---

## 📌 Features
- **Content-Based Filtering**: Uses cosine similarity between movies based on metadata.
- **Spelling Tolerance**: Handles closest match if the movie name is typed incorrectly.
- **Sentiment-Enhanced Ranking**: Boosts similarity scores for movies with positive-toned overviews, taglines, and keywords using VADER sentiment analysis.
- **Top 10 Recommendations**: Displays the most relevant movies for the user’s favorite.

---

## 📂 Dataset
The dataset used in this project is `Movies Recommendation.csv`, containing:
- **Movie_Title**
- **Movie_Genre**
- **Movie_Overview**
- **Movie_Tagline**
- **Movie_Keywords**
- **Movie_Cast**
- **Movie_Director**
- **Popularity, Revenue, Ratings** and more.

---

## ⚙️ Technologies Used
- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **VADER Sentiment Analysis**
- **FuzzyWuzzy** (for closest movie match)
- **Google Colab / Jupyter Notebook**

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/movie-recommendation-system.git
   cd movie-recommendation-system
2. Open the notebook in Google Colab or Jupyter Notebook.

3. Upload the dataset Movies Recommendation.csv.

4. Run all cells in order.

5. When prompted, enter your favorite movie name and get recommendations.

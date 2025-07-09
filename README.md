# 🎬 Simple Movie Recommendation System

This is a content-based movie recommender using movie overviews and TF-IDF similarity to suggest similar movies.

## 🎯 Objective
Recommend top 5 movies similar to a given movie based on plot descriptions.

## 📁 Dataset
- Files: `movies_metadata.csv`, optionally `credits.csv`
- Source: [Kaggle Movie Dataset](https://www.kaggle.com/datasets)
- Important column used: `overview`

## 🛠️ Tools Used
- Python
- pandas
- scikit-learn (TF-IDF Vectorizer, Cosine Similarity)
- Google Colab

## 🧪 Workflow
1. Load and clean dataset
2. Use TF-IDF to vectorize movie overviews
3. Compute cosine similarity
4. Create title-to-index mapping
5. Recommend top 5 similar movies

## 🚀 How to Run
1. Upload `movies_metadata.csv` to Google Drive
2. Mount Drive in Google Colab
3. Run `recommend_movies("Movie Title")` to get suggestions




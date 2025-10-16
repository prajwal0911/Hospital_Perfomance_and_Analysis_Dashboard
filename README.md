# 🎬 Movie Recommendation System  
### Personalized Content Discovery using Machine Learning  

This project implements an **intelligent Movie Recommendation System** that helps users discover movies tailored to their preferences using **machine learning**.  
It combines **Content-Based Filtering** and **Collaborative Filtering** techniques, deployed as an **interactive Streamlit web app**.

---

## 🚀 Features  
✅ Personalized movie recommendations  
✅ Integration with TMDb API for posters and details  
✅ Interactive and responsive Streamlit interface  
✅ Hybrid recommendation logic (content + collaborative)  
✅ End-to-end ML pipeline (data → model → deployment)

---

## 🧠 System Overview  
1. **Data Preprocessing** – Clean and prepare movie metadata.  
2. **Feature Extraction** – Use TF-IDF vectorization to convert text to numerical features.  
3. **Similarity Computation** – Use cosine similarity between movie vectors.  
4. **Recommendation Engine** – Retrieve and rank most similar movies.  
5. **Streamlit Deployment** – Simple, interactive web interface.

---

## 🗂️ Dataset & APIs  
- **Dataset:** [Kaggle - TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)  
- **APIs:**  
  - [OMDb API](https://www.omdbapi.com/) – For movie metadata.  
  - [TMDb API](https://www.themoviedb.org/documentation/api) – For posters & trailers.

---

## 💻 Tech Stack  

| Component | Technology |
|------------|-------------|
| Language | Python |
| ML Libraries | pandas, numpy, scikit-learn |
| Web Framework | Streamlit |
| API | TMDb |
| Deployment | Streamlit Cloud / Localhost |

---

## 🧩 Project Structure  


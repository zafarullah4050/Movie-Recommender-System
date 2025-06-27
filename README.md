# Movie-Recommender-System
# 🎬 Movie Recommender System

This is a **Content-Based Movie Recommendation System** built using **Python**, **Pandas**, **NLTK**, **Scikit-Learn**, and deployed via **Streamlit**. It recommends similar movies based on cast, crew, overview, genres, and keywords from the TMDB 5000 Movie Dataset.

---

## 🚀 Features

- Recommends 5 similar movies based on user input
- Uses NLP (Stemming & Vectorization) to process metadata
- Cosine similarity for finding most similar movie vectors
- Deployed with a simple and beautiful Streamlit interface

---

## 📁 Project Structure


---

## 🧠 How it Works

1. **Data Cleaning**: Extracts important columns (`genres`, `keywords`, `cast`, `crew`, `overview`)
2. **Preprocessing**: Uses `nltk.PorterStemmer` to stem the text
3. **Tag Creation**: Merges important fields into a single "tag" field
4. **Vectorization**: Uses `CountVectorizer` to convert text into vectors
5. **Similarity Matrix**: Calculates cosine similarity between vectors
6. **Recommendation**: Recommends top 5 most similar movies

---

## ▶️ How to Run Locally

1. Clone or download this repository
2. Ensure the following libraries are installed:

```bash
pip install streamlit pandas scikit-learn nltk

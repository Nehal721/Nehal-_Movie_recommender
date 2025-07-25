# Nehal-_Movie_recommender 🎬  
A content-based movie recommendation system using Streamlit and vectorization on a dataset of 5000 movies.

---

## 📌 Overview

This project leverages **Natural Language Processing (NLP)** & **Vectorization** to recommend similar movies based on user input. It analyzes metadata like genres, cast, and descriptions to deliver relevant suggestions.

---

## 🛠️ Tech Stack

- **Language**: Python  
- **Libraries**:  
  - `pandas` – data processing  
  - `numpy` – mathematical computations  
  - `scikit-learn` – vectorization & similarity  
  - `nltk` – text preprocessing  
- **Web Framework**: Streamlit

---

## 📂 Dataset

The dataset consists of 5000+ movies with attributes like title, genre, cast, and overview.  
It is preprocessed by handling missing values and combining relevant features.

---

## 🚀 How It Works

1. **Data Loading & Preprocessing**
   - Load dataset and select important columns.
   - Handle missing data.
   - Merge text features into a unified string.

2. **Text Processing**
   - Apply tokenization and stopword removal.
   - Perform stemming to reduce word redundancy.

3. **Vectorization & Similarity**
   - Use `CountVectorizer` or `TF-IDF` to convert text to vectors.
   - Apply **cosine similarity** to compute closeness between movies.

4. **Recommendation Logic**
   - User enters a movie name.
   - App returns the top N most similar movies based on vector similarity.

**Example:**  
Input: `Inception`  
Recommendations:
- Interstellar  
- The Prestige  
- Shutter Island  
- The Matrix  
- Memento

---

## 🎨 UI Design

The project includes a responsive web interface using **Streamlit**, making it interactive and user-friendly.

---

## 📈 Future Enhancements

- ✅ Hybrid models (collaborative + content-based)  
- ✅ More polished UI (web/mobile)  
- ✅ Deep learning integration for better accuracy  

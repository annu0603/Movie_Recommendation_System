# 🎬 Movie Recommendation System

This project implements a **Movie Recommendation System** that suggests movies to users based on similarity and preferences. It uses machine learning techniques and a movie dataset to generate personalized recommendations.

---

## 🚀 Project Overview
The goal of this project is to build a system that:
- Recommends movies similar to a selected title.  
- Uses content-based filtering (movie features such as genres, cast, crew, etc.).  
- Provides a user-friendly interface for interacting with recommendations.  

The system demonstrates how recommendation engines work and how machine learning can be applied to real-world applications like streaming platforms.

---

## 📂 Dataset
- Source: Movie dataset (commonly from **TMDB / IMDB datasets**)  
- Typical fields include:  
  - `movie_id`  
  - `title`  
  - `genres`  
  - `overview`  
  - `cast`  
  - `crew`  
  - `keywords`  

---

## 🧠 Methodology
- **Data Preprocessing** → Cleaning and structuring the dataset.  
- **Feature Extraction** → Combining important features like *overview, genres, keywords, cast, crew*.  
- **Text Vectorization** → Using **CountVectorizer / TF-IDF** to convert text to numerical format.  
- **Similarity Measurement** → Using **Cosine Similarity** to find movies closest to the input.  
- **Recommendation** → Returning the top N most similar movies.  

---

## 🛠 Tools & Technologies
- **Python** (Pandas, NumPy, Scikit-learn)  
- **Jupyter Notebook / Google Colab**  
- **HTML/CSS** for front-end output (if deployed as web page)  

---

## 📌 How to Use
1. Clone this repository.  
2. Install required libraries:  
   ```bash
   pip install pandas numpy scikit-learn
3. Run the notebook or script to generate recommendations.
4. Enter a movie name to get a list of recommended movies.

## 📷 Demo
<img width="238" height="425" alt="image" src="https://github.com/user-attachments/assets/508188bd-ef28-44ec-82a2-6d408652d6ad" />

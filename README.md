# 🎬 Movie Recommendation App using Machine Learning

A personalized movie recommendation system that suggests movies based on user preferences using content-based filtering and machine learning techniques. This project combines data science, web development, and user interaction to deliver a smart, responsive app for movie lovers.

---

## 🚀 Features

- ✅ Recommends movies based on similar genres, keywords, and overviews
- ✅ Clean and interactive UI
- ✅ Built with ML models for content-based filtering
- ✅ Real-time movie poster and details fetch using TMDB API
- ✅ Search bar to find movies quickly

---

## 🛠️ Tech Stack

| Area                  | Tools/Frameworks                          |
|-----------------------|-------------------------------------------|
| 💻 Programming        | Python, HTML, CSS, JavaScript             |
| 🤖 Machine Learning   | Scikit-learn, Pandas, Numpy               |
| 🗄️ Data Source        | TMDB 5000 Movie Dataset, TMDB API         |
| 🌐 Web Framework      | Streamlit / Flask                         |
| 🖼️ UI Enhancements     | Bootstrap / Custom CSS                    |
| 📦 Deployment         | Streamlit Share / Heroku / Render         |

---

## 📊 Machine Learning Approach

- **Content-Based Filtering** using:
  - TF-IDF Vectorizer for textual features (overview, genres, keywords)
  - Cosine Similarity to find similar movies
- Optional: KNN or collaborative filtering for future enhancements

---

## 🧪 How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/movie-recommender-ml.git
   cd movie-recommender-ml
2. **Install Dependencies**
  ```bash
  pip install -r requirements.txt
```
3. **Run the App**
 ```bash
 streamlit run app.py
```


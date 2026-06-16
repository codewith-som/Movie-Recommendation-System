# 🎬 Movie Recommendation System

A movie recommendation web application built using **FastAPI**, **Streamlit**, and **Machine Learning (TF-IDF)**. The system provides personalized movie recommendations based on movie similarity and genre matching using TMDB movie data.

## 🚀 Features

* 🔍 Search movies by title
* 🎬 View detailed movie information
* 🤖 TF-IDF based movie recommendations
* 🎭 Genre-based recommendations
* 🖼️ Movie posters and backdrops from TMDB
* ⚡ FastAPI backend for high-performance APIs
* 🎨 Modern Streamlit frontend

## 🛠️ Tech Stack

### Backend

* FastAPI
* Pandas
* Scikit-learn
* Requests

### Frontend

* Streamlit

### Machine Learning

* TF-IDF Vectorization
* Cosine Similarity

### Data Source

* TMDB API
* TMDB Movie Dataset

## 📂 Project Structure

```text
Movie-Recommendation-System/
│
├── app.py
├── main.py
├── requirements.txt
├── df.pkl
├── indices.pkl
├── tfidf.pkl
├── tfidf_matrix.pkl
├── movies_metadata.csv
├── .gitignore
└── README.md
```

## ⚙️ Installation

### 1. Clone Repository

```bash
git clone https://github.com/codewith-som/Movie-Recommendation-System.git
cd Movie-Recommendation-System
```

### 2. Create Virtual Environment

```bash
python -m venv .venv
```

### 3. Activate Virtual Environment

Windows:

```bash
.venv\Scripts\activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Create Environment Variable

Create a `.env` file:

```env
TMDB_API_KEY=YOUR_API_KEY
```

### 6. Run FastAPI Backend

```bash
uvicorn main:app --reload
```

Backend URL:

```text
http://127.0.0.1:8000
```

### 7. Run Streamlit Frontend

Open a new terminal:

```bash
streamlit run app.py
```

Frontend URL:

```text
http://localhost:8501
```

## 🎯 How It Works

1. User searches for a movie.
2. Movie details are fetched from TMDB.
3. TF-IDF similarity identifies movies with similar content.
4. Genre matching provides additional recommendations.
5. Results are displayed in a responsive Streamlit interface.

## 📸 Screenshots

Add your project screenshots here.

## 🔮 Future Improvements

* User authentication
* Hybrid recommendation system
* Watchlist feature
* Movie ratings and reviews
* Deployment on Render/AWS

## 👨‍💻 Author

**Som Shukla**

GitHub: https://github.com/codewith-som

## ⭐ Support

If you like this project, consider giving it a star on GitHub.

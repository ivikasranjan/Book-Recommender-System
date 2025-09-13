# 📚 Book Recommender System  

A machine learning–based Book Recommender System that suggests books to users using **Popularity-Based Filtering** and **Collaborative Filtering** techniques. The project is integrated with a **Flask web application** to provide real-time recommendations through an interactive interface.  

---

## 🚀 Features  
- **Popularity-Based Recommendation**: Suggests top books based on average ratings and number of reviews.  
- **Collaborative Filtering**: Recommends similar books using a user–item ratings matrix and cosine similarity.  
- **Interactive Web App**: Built with Flask, showcasing book covers, titles, and authors.  
- **Model Persistence**: Preprocessed data and similarity scores are stored as `.pkl` files for fast loading.  

---

## 🛠️ Tech Stack  
- **Languages & Libraries**: Python, Pandas, NumPy, Scikit-learn, Pickle  
- **Web Framework**: Flask  
- **Visualization**: Matplotlib, Seaborn (EDA)  
- **Frontend**: HTML, CSS, Jinja2 Templates  

---

## 📂 Project Structure  

Book-Recommender-System/
│
├── app.py # Flask application
├── books.csv # Dataset - books metadata
├── users.csv # Dataset - users metadata
├── Ratings.csv # Dataset - user ratings
├── popular.pkl # Popularity-based recommendation data
├── pt.pkl # Pivot table (book-user matrix)
├── books.pkl # Books metadata (processed)
├── similarity_scores.pkl # Cosine similarity matrix
│
├── templates/ # HTML templates
│ └── index.html
│
├── static/ # CSS / JS / images if any
├── requirements.txt
└── README.md


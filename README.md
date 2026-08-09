# 🎬 Netflix Movie Recommendation

A collaborative filtering–based recommendation system that suggests movies to users based on their viewing and rating patterns, built using Singular Value Decomposition (SVD).

---

## 📌 Overview

This project builds a movie recommendation engine using a large-scale Netflix ratings dataset. It applies collaborative filtering via SVD to learn latent patterns in user preferences and movie characteristics, generating personalized recommendations.

I built this project to deepen my understanding of recommendation systems, matrix factorization techniques, and handling large, sparse real-world datasets — skills directly relevant to data analytics and applied machine learning roles.

---

## 🎯 Objectives

- Process and analyze a large-scale movie ratings dataset
- Handle data sparsity typical of real-world recommendation problems
- Implement collaborative filtering using SVD for personalized recommendations
- Evaluate recommendation quality using standard metrics

---

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| Language | Python |
| Data Handling | Pandas, NumPy, SciPy |
| Modeling | Surprise / Scikit-learn (SVD implementation) |
| Visualization | Matplotlib, Seaborn |
| Environment | Jupyter Notebook |

---

## 📊 Key Features

- **Collaborative filtering engine** using SVD to factorize the user-item rating matrix into latent features
- **Handles large, sparse datasets** with efficient preprocessing and matrix representation
- **Personalized top-N recommendations** for any given user
- **Model evaluation** using RMSE/MAE to measure prediction accuracy
- **Exploratory analysis** of rating distributions, popular titles, and user activity patterns

---

## 📁 Project Structure

```
netflix-recommendation-engine/
│
├── data/                     # Ratings and movie metadata
├── notebooks/
│   ├── 01_data_preprocessing.ipynb
│   ├── 02_exploratory_analysis.ipynb
│   └── 03_svd_model_training.ipynb
├── models/                   # Saved trained model files
├── visuals/                  # Charts and evaluation plots
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/<your-username>/netflix-recommendation-engine.git
   cd netflix-recommendation-engine
   ```

2. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook
   ```bash
   jupyter notebook
   ```

4. Run notebooks in order: preprocessing → EDA → model training

5. Generate recommendations
   ```python
   from model import get_recommendations
   get_recommendations(user_id=123, n=10)
   ```

---

## 📈 Results & Insights

- Trained an SVD model on a large-scale ratings dataset, achieving strong prediction accuracy on held-out test data
- Generated meaningful top-N recommendations that align with user rating history
- Uncovered patterns in viewing behavior, including popular genres and rating distributions

*(Add specific numbers here once finalized — e.g., RMSE score, dataset size, number of users/movies)*

---

## 🔮 Future Improvements

- Combine collaborative filtering with content-based features (hybrid recommender)
- Deploy as an interactive web app using Streamlit or Flask
- Experiment with deep learning–based approaches (e.g., neural collaborative filtering)

---

## 👤 Author

**Suchith**
B.Tech Computer Science | Data Scientist Enthusiast

---

⭐ If you found this project useful, consider giving it a star!

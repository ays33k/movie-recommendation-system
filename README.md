# 🎬 Movie Recommendation System

A content-based movie recommendation system using TMDB dataset and Streamlit for an interactive frontend.

---

## 📦 Features

- Recommends movies based on similarity of features (genres, descriptions, etc.)
- Interactive UI built with Streamlit
- Utilizes machine learning and NLP techniques
- Easy to run and extend

---

## 🧠 Tech Stack

- **Python**
- **Pandas & NumPy**
- **Scikit-learn**
- **Streamlit**
- **Pickle for model persistence**
- **TMDB 5000 Movie Dataset**

---

## 🚀 How to Run the Project

### 1️⃣ Run the Jupyter Notebook

- Open `model.ipynb` using Jupyter Notebook.
- This script will preprocess the data, build the recommendation model, and **generate `.pkl` files**.

### 2️⃣ Move Pickle Files

- After running the notebook, ensure the generated `.pkl` files (like similarity matrix, vectorizer, etc.) are in the **same directory as `app.py`**.

### 3️⃣ Install Dependencies

pip install -r requirements.txt

### 4️⃣ Run the Streamlit App
streamlit run app.py

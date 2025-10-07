# 🎬 Movie Recommendation System

This project builds a **Movie Recommendation System** using **Python** and **Natural Language Processing (NLP)** techniques.  
It suggests movies based on user preferences, similarity of movie content, and metadata such as genres, cast, and keywords.

---

## 🚀 Features
- 🎥 Recommends similar movies based on a selected title  
- 🧠 Uses **cosine similarity** and **TF-IDF vectorization** for content-based filtering  
- 🧩 Clean and modular Python code  
- 💻 Works interactively in **Google Colab** or as a **Streamlit app**  
- ⚡ Easily extendable for larger datasets

---

## 🧠 Technologies Used
- **Python 3**  
- **pandas**, **numpy** – data handling and preprocessing  
- **scikit-learn** – NLP and similarity computation  
- **NLTK / spaCy** – text cleaning and tokenization  

---

## 📊 Dataset
The project uses publicly available movie metadata from:  
🎬 [TMDB Movie Dataset]
Dataset Link - (https://drive.google.com/file/d/1Psii9wZgKYc3hIcGFGllZIJTQ9epmaGF/view?usp=sharing)

---

## ⚙️ How It Works
1. Preprocess and clean movie metadata (genres, overview, keywords).  
2. Convert text data into numerical vectors using **TF-IDF**.  
3. Compute **cosine similarity** scores between all movies.  
4. Recommend top 5–10 most similar movies to the selected one.

---

## 🧩 Example Output
**Input:**  
> 🎞️ *Inception*  

**Recommendations:**  
- Interstellar  
- The Prestige  
- Shutter Island  
- Memento  
- The Matrix  

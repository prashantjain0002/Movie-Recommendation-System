# 🎬 Movie Recommendation System

The **Movie Recommendation System**, built with **Python** and leveraging **Pandas**, **NumPy**, **Streamlit**, **Scikit-learn**, and **Pickle**, offers personalized movie suggestions.  
It addresses the challenge of navigating vast movie collections by employing data analysis and machine learning. Users interact through Streamlit's user-friendly interface, inputting movie names for tailored recommendations.  
Pickle facilitates efficient storage of machine learning models, enhancing system speed. The collaborative filtering algorithm predicts preferences based on user behavior, refining suggestions for an engaging movie selection experience.

> Developed by [Prashant Jain](https://github.com/prashantjain0002)

---

## 🚀 Features

- 🎯 Personalized movie recommendations
- 🤖 Collaborative filtering based on user behavior
- 📊 Content-based filtering using cosine similarity
- 💾 Efficient model storage using Pickle
- 🌐 Interactive UI using Streamlit
- ⚡ Fast and responsive with precomputed similarity matrix

---

## 🧠 How It Works

1. The user enters a movie title.
2. The system processes similarity between movies using cosine similarity.
3. A pickled similarity matrix provides fast predictions.
4. Streamlit displays the top recommendations along with movie posters.

---

## 🖼️ Output Screenshots

### 🔎 Input Field and Results
![image](https://github.com/prashantjain0002/Movie-Recommendation-System-/assets/89723883/20c0f744-b756-4dd7-9538-b4009e0b2f56)

### 🧠 Movie Suggestions
![image](https://github.com/prashantjain0002/Movie-Recommendation-System-/assets/89723883/9e741bd1-47e2-441b-a7c5-cedf609d68a9)

### 🎬 Poster Display
![image](https://github.com/prashantjain0002/Movie-Recommendation-System-/assets/89723883/ef695b65-d8d9-4d91-b20f-00cbf6226c94)

---

## 🛠 Tech Stack

- **Python 3**
- **Pandas** and **NumPy** for data handling
- **Scikit-learn** for cosine similarity
- **Pickle** for storing model data
- **Streamlit** for the web app
- **IMDb/TMDB data** for movie metadata

---

## ⚙️ Setup Instructions (Step-by-Step)

### ✅ Prerequisites

Make sure you have the following installed:

- Python 3.7 or above
- pip (Python package installer)
- Git

---

### 📁 Project Structure
```bash
Movie-Recommendation-System/
│
├── app.py                  # Streamlit application
├── recommendation.py       # Core recommendation logic
├── similarity.pkl          # Pickled similarity matrix
├── movies.csv              # Movie dataset
├── requirements.txt        # Project dependencies
├── README.md               # Project documentation
└── ...
```

---

### 🔧 Step 1: Clone the Repository

```bash
git clone https://github.com/prashantjain0002/Movie-Recommendation-System.git
cd Movie-Recommendation-System
```
---

### 📦 Step 2: Install Dependencies
```bash
pip install streamlit pandas numpy scikit-learn requests
```

### 🚀 Step 3: Run the Streamlit App
```bash
streamlit run app.py
```

Then visit
🔗 http://localhost:8501 in your browser

---

### ⭐️ Support
If you found this project helpful, consider giving it a ⭐️ on GitHub — it helps others discover it too!

# 🌍 Tourism Analytics & Recommendation System
This project leverages data science and machine learning techniques to enhance tourism experiences through personalized recommendations, user satisfaction prediction, and behavior classification. By analyzing user preferences, travel patterns, and attraction features, this system aims to revolutionize how tourists discover and enjoy destinations.
## 🚀 Project Overview

**Tourism Analytics & Recommendation System** is an interactive web app designed to:
- Understand tourism trends through visual analytics
- Predict how travelers are likely to explore (Solo, Family, Group, etc.)
- Recommend personalized destinations based on user behavior and preferences

Whether you're a **traveler**, a **tourism board**, or a **data enthusiast**, this platform offers actionable insights to boost tourism experiences and strategies.

---

## 🎯 Key Features

### 📊 Trend Analysis
- Analyze **user demographics** (age, gender, income)
- Visualize **top-rated attractions** and **popular attraction types**
- Explore **visit mode distributions by region**

### 🧠 Visit Mode Prediction (ML)
- Predict how a traveler might explore (e.g., solo, family)
- Based on age, gender, income level, and country
- ✅ Powered by **Random Forest Classifier**
- 💡 View **feature importance** that explains decision logic

### 🔍 Personalized Recommendation Engine
- Suggests top destinations for a given **Visit Mode** and **Country**
- Optionally uses **collaborative filtering** (Cosine Similarity)
- Recommends what similar users have highly rated
- Highly customizable and easy to extend!

---

## 🧠 Machine Learning Behind the Scenes

### 1. 🎯 Random Forest Classifier
- Predicts **Visit Mode**
- Robust, interpretable, and handles mixed feature types
- Trained using user demographic and geographic features

### 2. 🔁 Collaborative Filtering (Cosine Similarity)
- User-based similarity model
- Suggests attractions rated highly by similar tourists
- Handles sparse rating matrices efficiently

---

## 🛠️ Tech Stack

| Layer            | Technology                        |
|------------------|------------------------------------|
| Frontend UI      | Streamlit                         |
| ML Algorithms    | Scikit-learn                      |
| Data Wrangling   | Pandas, NumPy                     |
| Visualization    | Seaborn, Matplotlib               |
| File Input       | Excel (.xlsx) Upload              |
| Recommendation   | Cosine Similarity (user-based)    |

---

## 📂 Folder Structure

📁 tourism_analytics/
├── app.py # Main Streamlit app
├── data/ # Example tourism data (optional)
├── models/ # Saved ML models (optional)
├── utils/ # Helper functions (optional)
├── requirements.txt # Python dependencies
└── README.md # Project documentation

yaml
Copy
Edit

---

## 🧪 How to Run

1. Clone this repo:
```bash
git clone https://github.com/your-username/tourism-analytics.git
cd tourism-analytics
Install requirements:

bash
Copy
Edit
pip install -r requirements.txt
Run the app:

bash
Copy
Edit
streamlit run app.py
Upload your Excel file with tourism data when prompted.

📈 Use Cases
📍 Tourism Boards: Understand tourist behavior and plan better infrastructure.

🧳 Travel Agencies: Offer personalized destination suggestions.

🧠 Researchers: Analyze mobility patterns and regional preferences.

💼 Business Analysts: Discover trends in travel economics.

🔮 Future Enhancements
Replace Excel upload with MySQL or live data streams

Add Deep Learning models (e.g., for sentiment analysis on reviews)

Integrate map-based visualizations using Folium or Mapbox

Deploy on cloud platforms like Heroku, AWS, or Streamlit Cloud

Introduce user login & profile history

👨‍💻 Developed By
Sham Prasath K. – Mechanical Engineering + AI Enthusiast
Built as part of an academic innovation project to combine machine learning with real-world travel data.

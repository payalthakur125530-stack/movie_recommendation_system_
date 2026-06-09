# 🎬 Movie Recommendation System using Machine Learning

A fully functional, interactive web application that recommends similar movies based on content filtering. This project uses machine learning algorithms to calculate movie similarities and features an intuitive user interface built with Streamlit, deployed live on the cloud.

🔗 **[Live Demo Link](https://movierecommendationsystem-ct7bdtnsmyc37huvyq47b5.streamlit.app)**

---

## 🚀 Features
* **Content-Based Filtering:** Analyzes movie tags, genres, and overviews to compute semantic similarity using textual features.
* **Interactive Dropdown UI:** Allows seamless searching and browsing across thousands of movies.
* **Instant Recommendations:** Generates the top 5 most relevant movie recommendations with a single click.
* **Cloud Architecture Optimization:** Built using **Git LFS (Large File Storage)** to seamlessly manage heavy machine learning matrices ($>100$ MB) on a production cloud environment.

---

## 🛠️ Tech Stack & Tools
* **Language:** Python
* **Web Framework:** Streamlit
* **Data Processing:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (CountVectorizer, Cosine Similarity)
* **Model Persistence:** Pickle
* **Version Control & Hosting:** Git, GitHub Desktop, Git LFS, Streamlit Community Cloud

---

## 📂 Project Architecture
```text
movie_recommendation_system/
├── app/
│   └── app.py            # Streamlit web interface & recommendation engine
├── .gitattributes        # Git LFS configuration track patterns
├── .gitignore            # Specifying untracked local directories
├── requirements.txt      # List of dependencies required for cloud compilation
├── movie_dict.pkl        # Compressed movie metadata dictionary
├── movies.pkl            # Cleaned movies DataFrame
└── similarity.pkl        # High-dimensional similarity matrix (175.8 MB via Git LFS)

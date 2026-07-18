# 🎵 Spotify Song Recommendation System

An intelligent **Music Recommendation System** built using **Machine Learning** that recommends songs based on their audio features and similarity. This project analyzes Spotify tracks and suggests songs with similar musical characteristics using content-based filtering.

---

## 🚀 Project Overview

Finding music that matches a listener's taste can be challenging when millions of songs are available. This project builds a **Content-Based Recommendation System** that compares songs based on their audio features such as danceability, energy, tempo, and acousticness to generate personalized recommendations.

Unlike popularity-based recommendations, this system focuses on the musical properties of each song, enabling users to discover tracks with a similar sound and feel.

---

## ✨ Features

* 🎵 Content-Based Music Recommendation
* 📊 Audio Feature Analysis
* 🔍 Fast Similar Song Search
* 📈 Data Preprocessing and Feature Scaling
* 🤖 Machine Learning-Based Similarity Search
* 📋 Clean and Modular Python Code
* 📁 Easy-to-Use Dataset Integration
* ⚡ Scalable Recommendation Pipeline

---

## 🛠️ Tech Stack

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

### Machine Learning

* StandardScaler
* Nearest Neighbors
* Cosine Distance

### Development Environment

* Jupyter Notebook
* VS Code
* Kaggle Notebook

---

## 📂 Project Structure

```text
Spotify-Recommendation-System/
│
├── data/
│   └── spotify_dataset.csv
│
├── notebooks/
│   └── Spotify_Recommendation.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── recommendation.py
│   └── utils.py
│
├── images/
│
├── requirements.txt
│
├── README.md
│
└── LICENSE
```

---

## 📊 Dataset

The project uses a Spotify songs dataset containing audio features such as:

* Song Title
* Artist
* Danceability
* Energy
* Valence
* Acousticness
* Tempo
* Loudness
* Speechiness
* Instrumentalness
* Popularity
* Duration

---

## ⚙️ Machine Learning Pipeline

### 1. Data Loading

* Import Spotify dataset
* Handle missing values
* Remove duplicates

### 2. Feature Engineering

Select meaningful numerical audio features.

### 3. Data Preprocessing

* Feature Scaling using StandardScaler
* Numerical feature normalization

### 4. Model Building

Instead of creating an enormous similarity matrix (which consumes significant RAM for large datasets), the project uses:

* Nearest Neighbors
* Cosine Distance Metric

This approach is memory efficient and scales well for large music collections.

### 5. Recommendation Generation

* User selects a song
* Model finds nearest songs
* Similar tracks are returned in ranked order

---

## 📈 Workflow

```text
Spotify Dataset
        │
        ▼
Data Cleaning
        │
        ▼
Feature Selection
        │
        ▼
Standard Scaling
        │
        ▼
Nearest Neighbors Model
        │
        ▼
Similarity Search
        │
        ▼
Top Recommended Songs
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Spotify-Recommendation-System.git
```

Move into the project folder:

```bash
cd Spotify-Recommendation-System
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

---

## 💻 Example Recommendation

**Input Song**

```
Shape of You
```

**Recommended Songs**

```
Perfect
Photograph
Thinking Out Loud
Castle on the Hill
Galway Girl
```

---

## 📊 Future Improvements

* Deep Learning Recommendation Models
* Hybrid Recommendation System
* Collaborative Filtering
* Streamlit Web Application
* Real-Time Spotify API Integration
* Mood-Based Recommendations
* Artist Similarity Search
* Playlist Generation
* User Authentication
* Personalized Recommendation History

---

## 📌 Requirements

```text
Python 3.10+

pandas
numpy
scikit-learn
matplotlib
seaborn
jupyter
```

Install all packages:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

---

## 📈 Results

* Fast recommendation generation
* Memory-efficient similarity search
* High-quality content-based recommendations
* Easily scalable for large Spotify datasets

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes.
4. Push to your branch.
5. Open a Pull Request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Abinesh M**

* AI & Data Science Student
* Machine Learning Enthusiast
* Data Analytics & Recommendation Systems
* Python | SQL | Power BI | Machine Learning

---

⭐ If you found this project useful, consider giving it a **Star** on GitHub!

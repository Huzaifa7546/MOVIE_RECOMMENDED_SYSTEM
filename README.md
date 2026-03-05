
# 🎬 Movie Recommendation System

A **Movie Recommendation System** built using **Python, Machine Learning, and Streamlit** that suggests movies based on user selection. The system uses **content-based filtering** to recommend similar movies based on their features such as genres, keywords, and cast.

The project provides an **interactive web interface using Streamlit**, allowing users to easily select a movie and receive recommended movies instantly.

---

# 🚀 Features

* Recommend movies based on similarity
* Content-based filtering algorithm
* Interactive web interface using Streamlit
* Fast movie search and recommendation
* Clean and simple UI
* Machine Learning powered recommendations

---

# 🛠️ Technologies Used

* **Python**
* **Machine Learning**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Streamlit**
* **Pickle**

---

# 📂 Project Structure

```
Movie-Recommendation-System
│
├── app.py                 # Streamlit web application
├── movies.pkl             # Movie dataset
├── similarity.pkl         # Similarity matrix
├── model.py               # Recommendation logic
├── requirements.txt       # Project dependencies
└── README.md              # Project documentation
```

---

# ⚙️ Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/yourusername/movie-recommendation-system.git
```

### 2️⃣ Navigate to the project folder

```bash
cd movie-recommendation-system
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Application

Start the Streamlit app using:

```bash
streamlit run app.py
```

After running the command, open the browser and go to:

```
http://localhost:8501
```

---

# 🧠 How It Works

1. The dataset contains information about movies such as title, genres, keywords, cast, and crew.
2. Data preprocessing is performed using **Pandas**.
3. Features are combined and converted into vectors.
4. **Cosine similarity** is used to calculate similarity between movies.
5. When a user selects a movie, the system recommends **top similar movies**.

---

# 📊 Machine Learning Technique

The system uses **Content-Based Filtering**:

* Feature Extraction
* Vectorization
* Cosine Similarity

This helps identify movies that are most similar to the selected movie.

---

# 💻 User Interface

The interface is built using **Streamlit**, allowing users to:

* Select a movie from a dropdown list
* Click the **Recommend** button
* View recommended movies instantly

---

# 📸 Demo

Example recommendation:

```
Input Movie: Avatar

Recommended Movies:
1. Guardians of the Galaxy
2. John Carter
3. Star Trek
4. Avengers
5. The Fifth Element
```

---

# 🔮 Future Improvements

* Add movie posters using TMDB API
* Deploy on **Streamlit Cloud / Render**
* Add collaborative filtering
* Improve UI design
* Add search functionality

---

# 👨‍💻 Author

**Huzaifa (Huzz)**
B.Tech IT | Aspiring Data Scientist

Skills:

* Python
* Machine Learning
* Data Analysis
* SQL
* Streamlit

---

# ⭐ Contribute

Contributions are welcome!
If you find this project useful, please **star the repository**.

---

# 🎵 Music Recommendation App (Python)

A **lyrics-based music recommendation system** that suggests similar songs using **content-based filtering**. The system analyzes song lyrics with **TF-IDF vectorization** and **cosine similarity** to recommend songs with similar themes and wording. The app is built in **Python** and deployed with **Streamlit** for an interactive user experience.

---

## ✨ Features

* 🎼 Content-based music recommendations
* 📝 Uses song lyrics as the primary feature
* 📊 TF-IDF vectorization for text representation
* 📐 Cosine similarity for measuring song similarity
* ⚡ Fast, interactive UI using Streamlit
* 🔍 Recommend songs based on a selected track

---

## 🛠️ Tech Stack

* **Python 3**
* **Pandas** – data handling
* **Scikit-learn** – TF-IDF & cosine similarity
* **Streamlit** – web app interface
* **NLTK / Regex (optional)** – text preprocessing

---

## 📊 Dataset

The dataset should include at least the following columns:

* `song` – Song title
* `artist` – Artist name
* `lyrics` – Full song lyrics

Example:

| song    | artist      | lyrics                       |
| ------- | ----------- | ---------------------------- |
| Imagine | John Lennon | Imagine there's no heaven... |

---

## 🚀 How It Works

1. **Text Preprocessing**

   * Lowercasing
   * Removing punctuation & stopwords (optional)

2. **Vectorization**

   * Convert lyrics into numerical vectors using **TF-IDF**

3. **Similarity Calculation**

   * Compute pairwise similarity using **cosine similarity**

4. **Recommendation**

   * Return top N most similar songs based on lyrics

---

## ▶️ Installation & Usage

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Shivaniii12/Music-Recommendation-App-
cd Music-Recommendation-App-
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Streamlit App

```bash
streamlit run app.py
```

---

## 🧪 Example Output

* Select a song from the dropdown
* Click **Recommend**
* Get a list of similar songs based on lyrics

---

Happy listening! 🎶

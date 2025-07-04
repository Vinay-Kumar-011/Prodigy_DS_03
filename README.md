
# 🐦 Twitter Sentiment Analysis with TextBlob

This project is focused on analyzing sentiments from a labeled dataset of tweets. The analysis leverages **TextBlob** for sentiment categorization and uses **visualization** to convey sentiment distribution—both overall and for a specific brand (Microsoft).

---

## 📁 Dataset

- **File**: `twitter_training.csv`
- **Structure**:  
  `['ID', 'Entity', 'Sentiments', 'Contest']`
  - `Entity`: Brand or keyword mentioned
  - `Sentiments`: Labeled sentiment (`Positive`, `Negative`, `Neutral`, etc.)

---

## 🧰 Libraries Used

- `pandas` – for data manipulation
- `TextBlob` – for sentiment analysis (library imported but not directly used in current code)
- `matplotlib.pyplot` – for visualization

---

## 📊 Workflow

### 1. Data Cleaning

- Reads the dataset and assigns column names.
- Drops:
  - Missing values
  - Duplicate entries

### 2. General Sentiment Analysis

- Counts the occurrences of each sentiment.
- **Visualized with**: Bar chart of sentiment distribution.

### 3. Brand-Based Analysis (Microsoft)

- Filters tweets related to **Microsoft**.
- Computes sentiment distribution specifically for this brand.
- **Visualized with**: Pie chart showing sentiment proportions.

---

## 📉 Sample Visualizations

- 📊 Bar Chart: Overall sentiment distribution
- 🥧 Pie Chart: Microsoft-related sentiment breakdown

---

## 🚀 How to Run

### Prerequisites

Install necessary Python libraries:
```bash
pip install pandas matplotlib textblob
```

### Steps

1. Clone/download this repository.
2. Place `twitter_training.csv` in the same folder as the notebook.
3. Open `Prodigy_DS_03.ipynb` in Jupyter Notebook.
4. Run the cells sequentially.

---

## 📌 Improvements to Consider

- Utilize `TextBlob` to **dynamically calculate polarity** of tweet text.
- Add preprocessing steps for raw tweet content (e.g., tokenization, stopword removal).
- Include sentiment prediction using machine learning models.

---

## 👨‍💻 Author

**Vinay Kumar**  
_Artificial Intelligence & Data Science Enthusiast_  


---

## 📃 License

This project is for educational and non-commercial use.

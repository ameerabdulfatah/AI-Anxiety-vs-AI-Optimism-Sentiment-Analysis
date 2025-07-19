
# AI Anxiety vs AI Optimism — Twitter Sentiment Analysis 🧠🤖💬

This project analyzes public sentiment on Twitter about Artificial Intelligence, focusing on the contrast between **AI Anxiety** and **AI Optimism**.

## 📌 Project Objective

To explore how people perceive the impact of AI using real-world tweets, and analyze their sentiment to identify trends, concerns, and excitement regarding artificial intelligence.

---

## 🧰 Tools & Technologies Used

- **Python**
- **Tweepy / Twitter API v2**
- **Pandas / Numpy**
- **Matplotlib / Seaborn**
- **NLTK / TextBlob**
- **WordCloud**
- **Jupyter Notebook**

---

## 📂 Dataset

- Data was collected using the Twitter API (search endpoint).
- Keywords used: `"AI Anxiety"`, `"AI Optimism"`.
- Tweets fetched: **75 English tweets** (due to API rate limits).
- Stored as: `ai_sentiment_cleaned.csv`

---

## 📊 Analyses Performed

### 1. Sentiment Classification
- Categorized tweets as **Positive**, **Neutral**, or **Negative** using TextBlob.

### 2. Sentiment Distribution Bar Chart

### 3. Word Cloud
Separate word clouds for all tweets to highlight common words.

### 4. Tweet Length by Sentiment
Average number of characters in tweets, grouped by sentiment.

### 5. Word Count Distribution
Distribution of total number of words used in tweets.

### 6. Bigram Analysis
Most frequent two-word combinations (bigrams) from all tweets.

---

## 🔍 Insights

- Many tweets about **AI Anxiety** expressed concern about jobs, surveillance, and safety.
- Optimistic tweets focused on **innovation**, **efficiency**, and **healthcare improvements**.
- Sentiment was **mixed**, with a slight lean toward optimism.

---

## 📷 Sample Visuals

![Word Cloud](images/wordcloud.png)
![Bigram Plot](images/bigram_plot.png)

> *(Images above are placeholders. Replace them with the actual exported chart images from your analysis.)*

---

## 📎 How to Run

1. Clone the repo
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

---

## ✅ Folder Structure

```
AI-Anxiety-vs-AI-Optimism-Sentiment-Analysis/
│
├── tweets_data.csv
├── notebook.ipynb
├── README.md
├── requirements.txt
└── images/
    ├── sentiment_chart.png
    ├── wordcloud.png
    ├── tweet_length.png
    └── bigram_plot.png
```

---

## 💡 Future Enhancements

- Use VADER or BERT for more accurate sentiment.
- Increase tweet count using elevated API access.
- Perform trend analysis over time (if timestamps are available).

---

## 🙌 Acknowledgement

Thanks to Twitter API and the open-source Python ecosystem for enabling this project.

---

## 📫 Contact

Made with ❤️ by Ameer Abdul Fatah  
[GitHub Profile](https://github.com/ameerabdulfatah)

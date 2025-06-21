# Sentiment Analysis 

This project is a web-based sentiment analysis tool developed using **FastAPI**, **JavaScript**, and **HTML/CSS**. It allows users to input multiple tweets (or text statements), and analyzes their sentiment using **VADER SentimentIntensityAnalyzer** from the NLTK library.

## 🚀 Features

* Add and remove multiple tweet entries dynamically.
* Analyze tweet sentiment with real-time results.
* Classifies sentiments into **positive**, **neutral**, and **negative**.
* Displays a **running average sentiment score**.
* Filters out non-English tweets automatically using `langdetect`.

## 🛠️ Tech Stack

* **Backend**: Python, FastAPI, NLTK (VADER)
* **Frontend**: HTML, CSS, JavaScript
* **Language Detection**: langdetect
* **API Communication**: Fetch API (POST request)

## 🔧 Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/Utkarsh0723/Sentiment_Analysis.git
   cd Sentiment_Analysis
   ```

2. Create a Python environment and install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the FastAPI server:

   ```bash
   uvicorn main:app --reload
   ```

4. Open `index.html` in your browser.

## 📊 Example Output

* Positive Count: 4
* Neutral Count: 2
* Negative Count: 1
* Running Average Sentiment Score:
  `[0.57, 0.42, 0.33, ...]`

## ✨ UI Preview

The interface is simple, responsive, and clean. Tweets are entered in a text area, and sentiment results are presented below in a styled result block.




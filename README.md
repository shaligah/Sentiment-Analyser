# ✈️ Heathrow Airport Review Sentiment Analysis  

Welcome aboard! 🛫  
This project scrapes **real passenger reviews** of **London Heathrow Airport** from [AirlineQuality.com](https://www.airlinequality.com/airport-reviews/london-heathrow-airport/) and runs them through a **sentiment analysis pipeline** to see what travelers *really* think.  

Using **NLTK’s VADER Sentiment Analyzer**, reviews are classified into:  
- 😀 Positive  
- 😐 Neutral  
- 😡 Negative  

All while giving each review a neat little sentiment score! 📊  

---

## 🚀 Features  

- 🔎 **Web Scraping**: Collects hundreds of reviews across multiple pages with `requests` + `BeautifulSoup`.  
- 🗂 **Data Handling**: Cleans and organizes text into a Pandas DataFrame.  
- 💡 **Sentiment Analysis**: Uses VADER’s pre-trained lexicon for fast, reliable sentiment scoring.  
- ⚡ **Pipeline Integration**: Built with `scikit-learn` pipeline for modularity.  
- 📝 **Reusable Functions**: Easily adapt the scraper & analyzer for other airports or airlines.  

---

# 🐦 Twitter Sentiment Analysis

This project analyzes Twitter data to uncover public sentiment trends and support marketing strategy using simulated sentiment labels, data visualization, and exploratory analysis.

## 🧰 Tools Used
- Python (Pandas, Matplotlib)
- Tableau (for dashboards)
- Jupyter Notebook

## 📌 Key Features
- Simulated a realistic Twitter dataset with labeled sentiments
- Performed EDA to detect sentiment shifts and trending hashtags
- Visualized audience engagement using charts
- GitHub-ready structure for portfolio presentation

## 🗂️ File Structure
- `data/`: raw + cleaned tweet datasets
- `notebooks/`: EDA and sentiment distribution notebook
- `visuals/`: Dashboard screenshot
- `README.md`: Project overview

## 🚀 How to Run
1. Clone the repo or download the zip
2. Open `notebooks/sentiment_analysis_large.ipynb`
3. Install dependencies: `pip install -r requirements.txt`
4. Run the notebook to explore data and sentiment visualization

Insights

Most tweets leaned positive, showing upbeat social chatter
#AI, #innovation, and #customerlove trended high
Morning tweets (especially Mondays 👀) carried stronger positive tone
Negative sentiment usually spiked around product complaints

⚠️ Limitations

Data is simulated, not pulled from the live Twitter API
Sentiment labels are mocked, not model-generated
No deep NLP models (like BERT or VADER) used yet
No streaming or geo-based analysis — yet 😉

🌱 What’s Next

Connect to Twitter API / Tweepy for real-time data
Integrate VADER or BERT for true sentiment detection
Add topic modeling (LDA) to find hidden discussion themes
Publish the Tableau dashboard online
Extend it to compare Twitter vs Instagram sentiment

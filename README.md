# 🔍 AI-Powered Customer Feedback Analysis Dashboard

An NLP-based customer feedback analytics system that combines sentiment analysis and automated topic extraction to transform unstructured customer reviews into actionable business insights.

## 🎯 Problem Statement

Businesses receive thousands of customer reviews but struggle to identify recurring complaints, customer satisfaction patterns, and areas requiring improvement. Manual analysis is time-consuming and traditional rating-based analysis often fails to capture the actual reasons behind customer dissatisfaction.

## ✨ Solution

This project uses Natural Language Processing (NLP) and data analytics to:

- Analyze customer reviews using sentiment analysis.
- Identify recurring customer concerns through topic extraction.
- Categorize feedback into 5+ business-relevant categories.
- Visualize sentiment trends and customer feedback patterns.
- Generate automated executive summaries.

## 🚀 Key Features

### 📊 Sentiment Analysis
- Positive, Negative and Neutral sentiment classification.
- Sentiment distribution analysis.
- Rating-based sentiment analysis.
- Identification of negative customer feedback.

### 🤖 NLP-Based Topic Extraction
- Automated extraction of customer concerns.
- Categorization into 5+ customer concern categories.
- Identification of recurring feedback patterns.
- Keyword-based topic identification.

### 📈 Interactive Dashboard
- Interactive Streamlit dashboard.
- Dynamic filters for sentiment and ratings.
- Sentiment trends and rating analysis.
- Visual representation of customer feedback.
- Automated executive summaries.

## 🛠️ Tech Stack

| Category | Technologies |
|---|---|
| Programming | Python |
| Data Processing | Pandas, NumPy |
| NLP | NLTK, TextBlob |
| Sentiment Analysis | VADER |
| Topic Extraction | NLP, Keyword Matching |
| Visualization | Plotly, Matplotlib |
| Dashboard | Streamlit |

## 📦 Installation

### Prerequisites
- Python 3.8+
- pip package manager
- Git

### Setup Instructions

**1. Clone the repository**

```bash
git clone https://github.com/yourusername/customer-insights-dashboard.git
cd customer-insights-dashboard
```

**2. Create a virtual environment**

```bash
python -m venv venv
```

Activate it:

```bash
# Windows
venv\Scripts\activate

# Linux / Mac
source venv/bin/activate
```

**3. Install dependencies**

```bash
pip install -r requirements.txt
```

**4. Run the application**

```bash
streamlit run app.py
```

## 📊 Project Workflow

1. **Data Collection:** Load customer review dataset.
2. **Data Preprocessing:** Handle missing values, duplicates and clean textual data.
3. **Exploratory Data Analysis:** Analyze ratings, review distributions and patterns.
4. **Sentiment Analysis:** Classify reviews into positive, negative and neutral categories.
5. **Topic Extraction:** Identify and categorize recurring customer concerns.
6. **Visualization:** Build interactive charts and dashboards.
7. **Executive Summary:** Generate meaningful insights from customer feedback.

## 📈 Key Insights

The project focuses on identifying:

- Overall customer sentiment distribution.
- Frequently reported customer complaints.
- Customer satisfaction across different ratings.
- Recurring product and service-related issues.
- Important patterns in negative customer feedback.

## 📸 Screenshots

Add your actual project screenshots here.

### Dashboard Overview

![Dashboard Overview](screenshots/dashboard.png)

### Sentiment Analysis

![Sentiment Analysis](screenshots/sentiment.png)

### Topic Extraction

![Topic Extraction](screenshots/topics.png)

### Customer Insights

![Customer Insights](screenshots/insights.png)

## 🏗️ Project Structure

```text
customer-insights-dashboard/
│
├── data/
│   └── reviews.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── sentiment_analysis.py
│   ├── topic_extraction.py
│   └── insights.py
│
├── screenshots/
│   ├── dashboard.png
│   ├── sentiment.png
│   ├── topics.png
│   └── insights.png
│
├── app.py
├── requirements.txt
├── README.md
└── .gitignore
```

*Adjust the structure according to your actual project files.*

## 🔮 Future Enhancements

- Transformer-based sentiment classification.
- Advanced topic modelling using LDA and BERTopic.
- Aspect-based sentiment analysis.
- Multilingual customer feedback analysis.
- Real-time customer feedback monitoring.
- AI-powered recommendations for business improvements.

## 📚 Applications

- **E-commerce:** Understand customer satisfaction and product complaints.
- **Customer Support:** Identify recurring customer issues.
- **Product Management:** Discover areas for product improvement.
- **Business Analytics:** Make data-driven decisions.
- **Marketing:** Understand customer preferences and feedback.

## 👤 Author

**Yash Mistry**

B.Tech Undergraduate | IIT Kharagpur

- GitHub: https://github.com/YOUR_USERNAME
- LinkedIn: https://linkedin.com/in/YOUR_PROFILE

---

**Built with Python, NLP and Streamlit ❤️**

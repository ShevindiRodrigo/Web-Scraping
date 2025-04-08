
# 🕸️ Web Scraping and Text Analysis of Data Analyst Jobs from Indeed

This project involves scraping job listings for Data Analyst roles from [Indeed](https://au.indeed.com/) using Python. It extracts job title, company, location, salary, and job description information, performs text processing and NLP to analyze job descriptions, and visualizes the most common keywords and phrases.

## 📌 Features

- Scrape job listings from multiple pages using BeautifulSoup and ScrapingDog API.
- Extract details such as Job Title, Company, Location, Salary, and Description.
- Preprocess job descriptions using NLTK (tokenization, punctuation removal, stopwords filtering, stemming, and lemmatization).
- Generate word, bigram, and trigram frequency distributions.
- Visualize top keywords and n-grams using Matplotlib and Seaborn.
- Export job listing data to a CSV file.

## 🧰 Technologies Used

- `Python`
- `BeautifulSoup` - for parsing HTML
- `Requests` - for HTTP requests
- `NLTK` - for natural language processing
- `Pandas` - for data manipulation
- `Matplotlib` and `Seaborn` - for data visualization

## 📂 Project Structure

```
.
├── jobs_data_analyst.csv          # Final cleaned dataset
├── requirements.txt               # Required Python packages
├── README.md                      # This file
└── Indeed.com web scraping.ipynb                 # Python script containing the code
```

## ⚙️ Installation

1. Clone this repository or download the files.
2. Install the required packages:

```bash
pip install -r requirements.txt
```

## 🚀 Usage

Run the script using:

```bash
python Indeed.com web scraping.ipynb
```

It will scrape job listings, clean the data, export to CSV, and display the visualizations.

## 📊 Sample Output

- Top 30 most frequent words
- Top 30 bigrams and trigrams
- Frequency plot of stemmed keywords in job descriptions

## 🔑 API Usage

This project uses the [ScrapingDog API](https://www.scrapingdog.com/) to bypass bot protection. Replace the API key in the script with your own for full access.

## 📝 License

This project is for educational purposes only.

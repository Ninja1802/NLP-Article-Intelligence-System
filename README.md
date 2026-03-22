# NLP-Article-Intelligence-System
### Automated Web Scraping & Text Intelligence Pipeline

## 📌 Overview

InsightMiner-NLP is an end-to-end Natural Language Processing (NLP) pipeline that automatically extracts textual data from web articles and performs advanced linguistic and sentiment analysis.

The system is designed to transform raw web content into structured insights by combining web scraping, text preprocessing, sentiment scoring, and readability analysis.

---

## ⚙️ What This Project Does

🔹 Extracts article content from given URLs
🔹 Cleans and preprocesses text using NLP techniques
🔹 Performs sentiment analysis using custom dictionaries
🔹 Computes readability and linguistic metrics
🔹 Stores extracted articles and structured results

---

## 🧠 Key Features

* 🌐 **Automated Web Scraping**

  * Extracts title and article content from webpages

* 🧹 **Text Preprocessing**

  * Tokenization (NLTK)
  * Stopword removal
  * Noise cleaning

* 😊 **Sentiment Analysis**

  * Positive score
  * Negative score
  * Polarity score
  * Subjectivity score

* 📊 **Text Analytics**

  * Average sentence length
  * Complex word count
  * Fog Index
  * Word count & syllables
  * Personal pronouns detection

* 📁 **Output Generation**

  * Extracted articles saved as `.txt`
  * Final analysis saved in `.xlsx`

---

## 🏗️ Project Structure

```
├── Input.xlsx
├── MasterDictionary/
│   ├── positive-words.txt
│   ├── negative-words.txt
├── StopWords/
├── extracted_articles/
├── output/
│   └── Output_Data.xlsx
├── main.ipynb
```

---

## ⚡ Prerequisites

Make sure you have:

* Python 3.x
* Google Colab / Jupyter Notebook
* Required libraries:

```bash
pip install beautifulsoup4 requests pandas openpyxl nltk textstat
```

Also download NLTK resources:

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
```

---

## 🚀 How to Run

### Step 1: Setup

* Place all required folders:

  * `MasterDictionary`
  * `StopWords`
  * `Input.xlsx`

### Step 2: Update Paths

Modify base paths in the notebook:

```python
BASE_PATH = 'your/local/or/drive/path/'
```

---

### Step 3: Run the Notebook

Execute all cells sequentially:

* Articles will be scraped
* Text will be processed
* Metrics will be calculated

---

### Step 4: Outputs

📄 Extracted Articles → `/extracted_articles/`
📊 Final Results → `/output/Output_Data.xlsx`

---

## 📈 Use Cases

* Content analysis for blogs/news
* Sentiment tracking
* SEO & readability analysis
* Data pipelines for NLP projects
* Research & academic applications

---

## 🧩 Tech Stack

* Python
* BeautifulSoup (Web Scraping)
* NLTK (Natural Language Processing)
* Pandas (Data Handling)
* Textstat (Readability Metrics)

---

## ✨ Future Improvements

* Add machine learning-based sentiment analysis
* Build API for real-time processing
* Deploy as a web application
* Add dashboard visualization

---

## 👨‍💻 Author

Developed as a practical NLP pipeline demonstrating real-world text analytics and data extraction capabilities.

---

## ⭐ If you found this useful

Give it a star ⭐ and feel free to fork!

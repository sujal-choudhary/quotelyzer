# 🧠 Quotelyzer - Quote Scraper using Jupyter Notebook

**Quotelyzer** is a web scraping and data analysis project built in **Jupyter Notebook** using **Python**, **BeautifulSoup**, and **pandas**. It scrapes inspirational quotes, authors, and tags from [quotes.toscrape.com](https://quotes.toscrape.com), saves them to a CSV file, and provides insights such as how many quotes each author has contributed.

---

## 🔍 Features

- Scrapes quote text, author name, and related tags from multiple pages
- Stores all data in a well-structured `quotes.csv` file
- Displays total number of **unique authors**
- Shows how many **quotes each author** has written
- Built for learning and practicing **web scraping** and **data analysis**

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/quotelyzer.git
cd quotelyzer
````

### 2. Install Required Libraries

Install dependencies listed in `requirements.txt`:

```bash
pip install -r requirements.txt
```

### 3. Open and Run the Notebook

Start Jupyter and open the scraper notebook:

```bash
jupyter notebook quote.ipynb
```

Then run all the cells to start scraping and analyzing data.

---

## 📁 Project Structure

```
quotelyzer/
├── quote.ipynb              # Main scraping and analysis notebook
├── quotes.csv               # Output file (generated after running notebook)
├── README.md                # Project documentation
└── requirements.txt         # List of Python packages required
```

---

## 📊 Output Example

### ✅ Console Output

```
Total Unique Authors: 10

Quotes per Author:
- Albert Einstein: 5 quote(s)
- Jane Austen: 2 quote(s)
- J.K. Rowling: 3 quote(s)
...
```

### ✅ CSV File Preview

| Text                                                  | Author         | Tags                       |
| ----------------------------------------------------- | -------------- | -------------------------- |
| "Be yourself; everyone else is already taken."        | Oscar Wilde    | be-yourself, inspirational |
| "So many books, so little time."                      | Frank Zappa    | books, reading             |
| "A room without books is like a body without a soul." | Marcus Tullius | books, soul, inspirational |

---

## 💡 Educational Purpose

This project scrapes data from [quotes.toscrape.com](https://quotes.toscrape.com), a public site designed specifically for practicing web scraping. It is **100% legal and ethical** for educational use.

---

## 👨‍💻 Author

**Sujal Choudhary**

Student | Full Stack Developer | Python & AI Enthusiast


---

## 📄 License

This project is licensed under the **MIT License** – feel free to use, modify, and share.

---

## 🏷️ GitHub Topics

> Add these to your repository topics:

```
python  web-scraping  jupyter-notebook  pandas  beautifulsoup  data-analysis  quotes
```




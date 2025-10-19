# 📘 Web Scraping Books Data using Python
### CodeAlpha Data Analytics Internship — Task 1

---

## 📌 Project Overview
This project demonstrates **web scraping** of book data from [BooksToScrape.com](https://books.toscrape.com/), a free and legal website for practicing scraping.

The goal is to **extract useful information** like:
- Book titles  
- Prices  
- Ratings  
- Availability status  

and create a **clean dataset** for analysis and visualization.

This dataset can also be used for future tasks such as **Exploratory Data Analysis (EDA)** and **Sentiment Analysis**.

---

## 🛠 Tools & Libraries
- Python 3  
- `requests` — to fetch HTML content  
- `BeautifulSoup` — to parse HTML  
- `pandas` — for data cleaning and storage  
- `matplotlib` — for data visualization  

---

## 🧩 Workflow
1. **Fetch HTML** from multiple pages of BooksToScrape.com  
2. **Parse HTML** using BeautifulSoup to extract book information  
3. **Store data** in a structured Pandas DataFrame  
4. **Clean & process** data (convert price to numeric, map ratings)  
5. **Save dataset** as CSV for future analysis  
6. **Visualize insights** — ratings distribution and price distribution  

---

## 📊 Dataset Preview

| Title                                   | Price (£) | Rating | Availability |
|----------------------------------------|-----------|--------|--------------|
| A Light in the Attic                    | 51.77     | 3      | In stock     |
| Tipping the Velvet                      | 53.74     | 1      | In stock     |
| Soumission                              | 50.10     | 1      | In stock     |
| Sharp Objects                           | 47.82     | 4      | In stock     |
| Sapiens: A Brief History of Humankind  | 54.23     | 5      | In stock     |

> ✅ CSV File: `books_to_scrape_dataset.csv`

---

## 📈 Visualizations

### 1. Rating Distribution
Bar chart showing the number of books with 1–5 stars.

### 2. Price Distribution
Histogram showing the spread of book prices.

> These visualizations provide quick insights into the **quality and pricing trends** of the books.

---

## 💡 Insights from Dataset
- Total Books Scraped: **100+ (depending on pages scraped)**  
- Average Price: **£XX.XX**  
- Most Frequent Rating: **X stars**  
- Highest Priced Book: **£XX.XX**  
- Lowest Priced Book: **£XX.XX**  

---

## 🚀 How to Run
1. Open `web_scraping_books.ipynb` in **Google Colab** or **Jupyter Notebook**  
2. Run all cells to fetch live data  
3. The dataset will be saved automatically as `books_to_scrape_dataset.csv`  
4. Visualizations will display within the notebook  

---

## 🔗 Project Folder Structure
CodeAlpha_WebScraping_BooksDataset/
│
├── Code Alpha Task 1.ipynb
├── books_to_scrape_dataset.csv
└── README.md


---

## 👨‍💻 Author
**Your Name** — CodeAlpha Data Analytics Intern  
GitHub: [https://github.com/yourusername]([https://github.com/yourusername](https://github.com/SatyanarayanaG2908/CodeAlpha_WebScraping_BooksDataset))

---

## 📌 References
- [Books to Scrape](https://books.toscrape.com/)  
- [BeautifulSoup Documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)  
- [Python Requests Library](https://docs.python-requests.org/)


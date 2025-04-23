# Web Scraping Top US Companies from Wikipedia

This is a beginner-friendly web scraping project where I used Python to scrape a list of the **largest companies in the United States by revenue** from Wikipedia and converted it into a structured dataset.

---

## 📌 Objective

The goal of this project was to:
- Practice basic web scraping using **BeautifulSoup**
- Extract tabular data from a real-world webpage
- Clean and store the data using **Pandas**
- Export the final dataset into a **CSV file** for further analysis

---

## 🛠️ Tools & Libraries Used

- **Python**
- **BeautifulSoup** – for parsing HTML
- **Requests** – to make HTTP requests
- **Pandas** – for handling tabular data

---

## 🔍 Source

Data was scraped from:  
📎 [Wikipedia – List of largest U.S. companies by revenue](https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue)

---

## 📄 How It Works

1. Requested the page using `requests.get()`
2. Parsed the HTML using BeautifulSoup
3. Located the first table on the page
4. Pulled the table headers and rows
5. Stored the data into a Pandas DataFrame
6. Exported the data to a CSV file

---

## 🧪 Output

The final result is a clean `.csv` file named **companies.csv** containing a full list of the largest U.S. companies by revenue including:

- Company
- Industry
- Revenue
- Employees
- Headquarters location  
... and more depending on the table columns

---

## 📂 File Location

Make sure to update the CSV path based on your own directory when reusing the code.

```python
df.to_csv(r'YOUR/PATH/HERE/companies.csv', index=False)

---

## ✅ What I Learned
- Navigating HTML elements

- Extracting data from structured tables

- Converting raw web data into a usable format

- The basics of real-world web scraping


------

## 💡 Next Steps
In future versions, I plan to:

- Scrape multiple tables/pages

- Clean inconsistent entries

- Upload the data for visualization


Thanks for checking this out! 🚀

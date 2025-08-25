# Stock-Market-Analysis-Tesla-GME
Final project analyzing Tesla (TSLA) and GameStop (GME) stock &amp; revenue using yfinance and webscraping.
# 📊 Stock Market Analysis: Tesla (TSLA) & GameStop (GME)

This project analyzes the stock prices and revenues of **Tesla (TSLA)** and **GameStop (GME)** using:
- **yfinance** for stock data
- **Webscraping (BeautifulSoup, Requests)** for revenue data
- **Plotly** for interactive visualizations

It is part of the IBM Data Science Professional Project.

---

## 🚀 Project Structure

### 🔹 Question 1: Extract Tesla Stock Data
- Used `yfinance.Ticker("TSLA")` and `.history(period="max")`
- Reset index and displayed the first 5 rows.  
📸 Screenshot: `Q1.png`

---

### 🔹 Question 2: Extract Tesla Revenue Data
- Scraped revenue data using `requests` + `BeautifulSoup`
- Cleaned revenue column (removed `$` and `,`)
- Displayed last 5 rows.  
📸 Screenshot: `Q2.png`

---

### 🔹 Question 3: Extract GameStop Stock Data
- Used `yfinance.Ticker("GME")` and `.history(period="max")`
- Reset index and displayed the first 5 rows.  
📸 Screenshot: `Q3.png`

---

### 🔹 Question 4: Extract GameStop Revenue Data
- Scraped revenue data from HTML table
- Cleaned revenue column
- Displayed last 5 rows.  
📸 Screenshot: `Q4.png`

---

### 🔹 Question 5: Plot Tesla Stock Graph
- Used the provided `make_graph` function
- Graph plots **Tesla Stock Price vs Revenue**  
📸 Screenshot: `Q5.png`

---

### 🔹 Question 6: Plot GameStop Stock Graph
- Used the provided `make_graph` function
- Graph plots **GameStop Stock Price vs Revenue**  
📸 Screenshot: `Q6.png`

---

## 📂 Files in this Repository
- `stock_analysis.ipynb` → Main Jupyter Notebook with all code  
- `Q1.png – Q6.png` → Screenshots for each task  
- `README.md` → Project documentation (this file)  

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- yfinance  
- BeautifulSoup (bs4)  
- Requests  
- Plotly  

---

## ✅ Results
- Successfully extracted stock data & revenue for Tesla and GameStop  
- Created interactive graphs with Plotly  
- Cleaned revenue data for consistency  
- Delivered screenshots for all tasks  

---

## 🔗 Submission Link
GitHub Repository: [Your Repo Link Here]  

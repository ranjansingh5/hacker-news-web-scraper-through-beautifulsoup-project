# 📰 Hacker News Web Scraper (Python + BeautifulSoup)

## 📌 Project Overview

This project is a simple **web scraping application** built with **Python**, **Requests**, **BeautifulSoup**, and **Pandas**.
The script collects the latest news articles from **Hacker News** and saves them into a CSV file.

It extracts important information from the homepage such as:

* News Title
* Article Link
* Rank of the post

---

## Table of Contents

- [Data Source](data-source)
- [Features](features)
- [Technologies Used](technologies-used)
- [Project Structure](project-structure)
- [How the Script Works](how-the-script-works)
- [Output](output)
- [Learning Outcomes](learning-outcomes)
- [Author](author)

---

## 🌐 Data Source

Website used in this project:

https://news.ycombinator.com/

---

## 🚀 Features

* Scrapes latest posts from Hacker News homepage
* Extracts article title, link, and ranking
* Cleans text using `.strip()`
* Stores results in a **Pandas DataFrame**
* Exports data into a **CSV file**

---

## 🛠️ Technologies Used

* **Python**
* **requests** – for sending HTTP requests
* **BeautifulSoup (bs4)** – for parsing HTML
* **pandas** – for data handling and exporting CSV

---

## 📂 Project Structure

```
hacker_news_scraper.py
Hacker_News.csv
README.md
```

---

## ⚙️ How the Script Works

1. Send an HTTP request to the Hacker News homepage.
2. Parse the HTML content using BeautifulSoup.
3. Find all news article containers.
4. Extract:

   * Article title
   * Article link
   * Article rank
5. Store the extracted data in a Python list.
6. Convert the list into a Pandas DataFrame.
7. Export the DataFrame to a CSV file.

---

## 📊 Output

The script generates a CSV file named:

```
Hacker_News.csv
```

Example dataset format:

| Title           | Link                | Rank |
| --------------- | ------------------- | ---- |
| Example Article | https://example.com | 1    |
| Example Article | https://example.com | 2    |

---

## 🎯 Learning Outcomes

This project helps you understand:

* Basics of web scraping
* HTML parsing with BeautifulSoup
* Extracting structured data from websites
* Data handling using pandas
* Exporting datasets to CSV files

---

## 🧑‍💻 Author

**Author:** Ranjan Singh

**Project Type:** Web Scraping Project

**Language:** Python

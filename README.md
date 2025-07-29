# 🕸️ Web Scraping Python Project – Job Listings Extractor

This project demonstrates how to build a **web scraper** using Python to extract job listings from [TimesJobs](https://www.timesjobs.com/). It follows a practical, beginner-friendly approach to web scraping, based on the tutorial by [CodeWithHarry](https://www.youtube.com/watch?v=XVv6mJpFOb0).

---

## 📁 Project File

- `WebScraping.ipynb`: The main Jupyter Notebook containing all scraping logic, explanations, and examples.

---

## 🔍 What This Project Does

- Parses HTML from a saved page and from a live website.
- Extracts specific HTML elements like course names and job titles.
- Scrapes job postings from the TimesJobs website.
- Extracts useful details:
  - Company Name
  - Required Skills
  - Posting Date
  - Job Description Link
- Filters out jobs based on user-defined unfamiliar skills.
- Saves relevant jobs into organized `.txt` files.
- Automatically re-runs every 10 minutes to check for new postings.

---

## 📦 Requirements

To run this project, make sure you have the following Python packages installed:

- `beautifulsoup4`
- `lxml`
- `requests`

You can install them using `pip`.

---

## 🧠 Concepts Covered

- HTML structure basics (head, div, a, h5 tags, etc.)
- Using BeautifulSoup to:
  - Read and parse HTML files
  - Find specific tags and classes
  - Extract and clean text
- Using Requests to get HTML from live websites
- Automating data collection with time delays
- Saving output in a structured and readable format

---

## 🛠 How to Use

1. Clone the repository to your local machine.
2. Open `WebScraping.ipynb` in Jupyter Notebook or VS Code.
3. Run the cells to learn, modify, or run the scraper.
4. Enter the skill(s) you want to filter out when prompted.
5. Scraped jobs (excluding unfamiliar skills) will be saved in the `posts/` directory as `.txt` files.

---

## 📌 Source Tutorial

This project is inspired by and built based on:

🎥 [CodeWithHarry – Web Scraping Using Python](https://www.youtube.com/watch?v=XVv6mJpFOb0)

---

## 📂 Directory Structure


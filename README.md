# python_project-google-scrapper
# 📸 Google Image Scraper
# 🌟 Overview
This project is a web-based Image Scraping tool designed to automate the process of searching and downloading images from Google Search. Built with Flask and BeautifulSoup, it provides a simple interface where users can enter a search query, and the system automatically fetches, processes, and stores the resulting images locally. 📂

The application handles HTTP requests with custom headers to mimic browser behavior, ensuring reliable data extraction while managing local storage for the downloaded content.

# ✨ Features
Web-Based Interface: A clean UI built with Flask for easy user interaction. 🖥️

Automated Image Extraction: Leverages BeautifulSoup to parse HTML and isolate image tags. 🔍

Local Storage Management: Automatically creates directories and saves images with structured naming conventions (e.g., query_index.jpg). 💾

User-Agent Spoofing: Uses custom headers to prevent request blocking during scraping. 🛡️

Database Ready: includes pymongo integration logic for potential metadata storage. 🗄️

Logging System: Tracks server activity and errors in scrapper.log for easy debugging. 📝

# 🛠️ Technologies Used
Python: Core programming language. 🐍

Flask: Web framework for the backend API and routing. 🌐

BeautifulSoup4 (bs4): For parsing HTML and web scraping. 🥣

Requests: To handle HTTP GET/POST calls. 📡

PyMongo: For MongoDB database connectivity. 🍃

Logging & OS: For system-level operations and activity tracking. ⚙️

# 📊 Key Functionalities
Dynamic Query Processing: Replaces spaces and prepares search strings for Google’s image engine.

Directory Automation: Checks for the existence of an images/ folder and creates it if missing.

Binary Data Handling: Downloads raw image content and writes it directly to disk in .jpg format.

Error Handling: Implements try-except blocks with logging to capture and record runtime exceptions.


# Development Server: 
Configured with debug=True and a reloader for rapid development and testing.

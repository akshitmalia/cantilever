# Cantilever Cybersecurity Internship Tasks

This repository contains two completed tasks as part of the Cantilever internship in the field of Cybersecurity.

## Task 1: Web Scraper with Flask Interface

This project scrapes book data from a test e-commerce website and displays it using a web interface with search functionality.

### Features
- Scrapes book title, price, and rating
- Saves data into a CSV file (`books.csv`)
- Web UI built using Flask and HTML
- Real-time search bar to filter results by title

### Technologies Used
- Python 3.13
- Requests
- BeautifulSoup4
- Pandas
- Flask

### How to Run
1. Run the scraper script:
2. Start the Flask server:
3. Open your browser and go to:
     http://127.0.0.1:5000/



---

## Task 2: Keylogger with Screenshot Capture

This Python script logs all keystrokes and captures screenshots at regular intervals. Both logs and screenshots are saved in a timestamped folder.

### Features
- Logs every key pressed into `keystrokes.txt`
- Takes screenshots every 10 seconds
- Uses multithreading for parallel execution
- Cleanly exits with Ctrl + C

### Technologies Used
- Python 3.13
- pynput
- pyautogui
- threading
- datetime
- time
- os

### How to Run
1. Open terminal and activate the Python environment
2. Run the script:
     python keylogger.py
3. The script will begin logging keystrokes and capturing screenshots every 10 seconds
4. To stop the script, press:
     Ctrl + C




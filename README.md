# E-commerce Web Scraper with Search UI

This project scrapes book data from [books.toscrape.com](http://books.toscrape.com) and displays it using a Flask web interface with search functionality.

##  Features
- Scrapes book **Title, Price, Rating**
- Saves data into `books.csv`
- Search bar to filter books by title
- Flask-based user interface
- Clean, tabular display with dynamic filtering

##  Technologies Used
- Python 3.13
- Requests
- BeautifulSoup4
- Pandas
- Flask

##  Project Structure
```
cantilever_webscraper/
├── books.csv
├── scraper.py
├── app.py
├── templates/
│   └── index.html
├── static/
└── venv/ (not pushed to GitHub)
```

##  How to Run
1. Run the scraper:
   ```
   python scraper.py
   ```
2. Start the Flask server:
   ```
   python app.py
   ```
3. Visit `http://127.0.0.1:5000/` in your browser

##  Note
This project is part of my internship with **Cantilever Labs** under the Cybersecurity domain.


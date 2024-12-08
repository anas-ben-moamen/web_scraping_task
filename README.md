# Web Scraping Project

## Approach
The goal of this project is to scrape data from a provided HTML page and structure it into CSV and JSON formats. The scraping was performed using Python and **BeautifulSoup**, a powerful library for parsing HTML. For dynamic content that might be loaded using JavaScript, tools like **Selenium** can be used, but this project focuses on extracting data from static HTML content.

## Tools Used
- **Python**: The primary programming language used for scripting the web scraping tasks.
- **BeautifulSoup (bs4)**: Used for parsing the HTML content and extracting specific elements.
- **CSV Module**: Used to save data into CSV format.
- **JSON Module**: Used to save data into JSON format.

## Challenges Faced
- **HTML Structure**: Ensuring the correct class names and tags were targeted for data extraction required careful inspection of the HTML source code.
- **Dynamic Content**: If any part of the data was dynamically loaded via JavaScript, using **Selenium** would be necessary to handle this, but it was not needed for this task.
- **Data Cleaning**: Extracting clean text while ignoring extra spaces and formatting was essential for creating structured output.

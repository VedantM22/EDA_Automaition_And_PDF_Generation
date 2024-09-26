## Amazon Web Scraping Tool (scaper.ipynb)

# Overview:
This project is a web scraping tool designed to extract product details, including the name, price, and link from Amazon's e-commerce platform using Selenium and pandas. The primary focus is on automating the retrieval of this information and converting it into a well-structured format for further analysis.

# Key Features
Web Scraping with Selenium:
The project utilizes Selenium to automate the web browser, navigate through Amazon product listings, and extract the necessary information (product name, price, and link).
It employs browser automation techniques to handle dynamic page loading, ensuring that the required elements are fully loaded before extraction.

Data Storage:
The scraped data is stored in a pandas DataFrame with columns for Product, Price, and Links.
This structure ensures the data is easily accessible for further analysis or storage in external formats like CSV or databases.

Data Handling:
Basic error handling is incorporated to manage missing values and ensure no interruption during the scraping process.
The project demonstrates how to manage and save structured data after web scraping for use in various applications.

Libraries Used:
Selenium: For web scraping and browser automation.
pandas: For data manipulation and storage.

# Methodology & Advantages
Automation: Selenium automates the tedious process of manually collecting data, improving efficiency.
Structured Data: The scraped data is immediately organized into a structured format, which facilitates further analysis.
Versatility: The project can be easily extended to scrape other e-commerce platforms with minor modifications.

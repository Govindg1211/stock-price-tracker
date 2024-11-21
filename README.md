# stock-price-tracker
Overview
The Stock Price Tracker is a Python-based graphical user interface (GUI) application that allows users to track real-time stock prices from the National Stock Exchange (NSE) and Bombay Stock Exchange (BSE) in India. The application fetches stock prices using web scraping techniques and provides an intuitive interface for users to enter stock tickers, select exchanges, and view or manage their stock wishlist.

Prerequisites
To run this application successfully, you need to have Python installed on your system along with several libraries. Here’s a list of prerequisites:
Python: Ensure you have Python installed (preferably Python 3.x).

Required Libraries:
requests: For making HTTP requests to fetch stock data.
beautifulsoup4: For parsing HTML content.
tkinter: For creating the GUI (comes pre-installed with Python).
bse: For fetching BSE-related data (install using pip install bse).
Installation Instructions
Install Python from python.org.
Install required libraries using pip:

pip install requests beautifulsoup4 bse

Ensure you have an image file named stocks.png in your specified directory (write your image path here) for the background.

How to Use
Launch the application by running the Python script.
Enter a valid stock ticker symbol in the "Enter Stock Ticker" field.
Select either 'NSE' or 'BSE' from the dropdown menu.
Click "Fetch Price" to see the current price of the entered stock displayed on the screen.
To add a stock to your wishlist, click "Add to Wishlist." This will create a card showing the ticker and its current price.
To remove a stock from your wishlist, click the "Remove" button on its respective card.
The application will automatically update prices every 10 seconds.

Conclusion
This Stock Price Tracker application provides an effective way for users to monitor their favorite stocks in real time, manage their wishlist, and gain insights into market trends through an easy-to-use interface. With its combination of web scraping and GUI elements, it serves as a practical tool for both novice and experienced investors alike.


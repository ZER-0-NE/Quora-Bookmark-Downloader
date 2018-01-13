# Quora Bookmark Downloader

A Python Script to download bookmarked answers from Quora.com

# Dependencies

* selenium
* pyperclip
* pdfkit
* BeautifulSoup

# Install Dependencies

* selenium
  * `pip install selenium`
  
* pyperclip
  * `pip install pyperclip`
  
* pdfkit
  * `pip install pdfkit`
  
* BeautifulSoup
  * `pip install beautifulsoup4`

#### Note ####
1. pdfkit also require wkhtmltopdf

Install it from `https://wkhtmltopdf.org/downloads.html`

2. Chromedriver is required 

Install it from `https://sites.google.com/a/chromium.org/chromedriver/downloads`

3. Change `brow=webdriver.Chrome("/Users/Wolf/Desktop/chromedriver")` to `brow=webdriver.Chrome("/Users/USERNAME/Desktop/chromedriver")`

# Run

just run it from terminal/command prompt `python quorab.py`

### Note ###
After a new chrome window is opened, you have to just enter your account credentials and press `Enter` after that.


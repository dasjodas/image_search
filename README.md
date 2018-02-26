# image-scrappers
Image Scrappers built for scrapping Bing and Google images + metadata. Made for Python3.5

## How to Use

### Google:

Make sure you install the requirements by doing:
	pip install -r requirements.txt

Ensure you have the [appropriate version](https://sites.google.com/a/chromium.org/chromedriver/downloads) of ChromeDriver on your machine.

Then:
	python3.5 google-scraper.py "https://www.google.com/search?q=cats&source=lnms&tbm=isch&sa=X&ved=0ahUKEwiwoLXK1qLVAhWqwFQKHYMwBs8Q_AUICigB" cats


## FAQs

*Why do I ask for the url parameter?*
 - I am using the URL parameter so the user can specify tag searches as well (the rectangular suggestions on the top for google)
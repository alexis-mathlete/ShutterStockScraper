# ShutterScrape

ShutterScrape is a web scrapper for bulk downloading images and videos from [Shutterstock](https://www.shutterstock.com/) with speed. ⚡</br>
It implements [Selenium](https://www.seleniumhq.org/) for browser automation and [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) for parsing.

---

## Setting up

1. Configure `shutterscrape.py` to your Python version.

2. Install requirements from Terminal:
```
pip install beautifulsoup4
pip install selenium
pip install lxml
```

3. Install [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/downloads).

4. *(Optional)* [Configure environment variables paths](https://www.java.com/en/download/help/path.xml) for **python.exe** and **chromedriver.exe**.

---

## Running

Open terminal in the directory of **shutterscrape.py** and enter:
```
python shutterscrape.py
```
Go grab a cup of coffee while waiting... oh wait, it's already done!

---

## Definitions

* **Search mode**: Enter `i` for scraping images and `v` for scraping videos .
* **Number of search terms**: For example, if you want to search for *drone single person*, enter `3`.
* **Search term**: Keyword(s) for searching on Shutterstock.
* **Number of pages to scrape**: Higher number of pages means greater quantity of content with lower keyword precision.

---

## Updates

**10/1/2020**</br>
Updated for new shutterstock page layout as of 10/1/2020.

**4/26/2019**</br>
Updated for new shutterstock page layout as of 4/26/2019.

**10/1/2018**</br>
Added GUI for save directory selection.

**07/31/2018**</br>
More stability fixes.

**07/25/2018**</br>
Added **gettyscrape.py** for scraping videos from [Getty Images](https://www.gettyimages.com/footage/).

**07/23/2018**</br>
Stability fixes.
#ShutterStockScraper

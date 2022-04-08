# **Mission-to-Mars**
HTML Web scraping on Mars data to create a Flask web application using Python and MongoDB_

## **Overview**

This project consisted on a Python script to scrape text and images from various websites that talked about Mission to Mars. Then, I created a Flask web application with a rendered HTML template designed using Bootstrap to display all the data in a central location without having to gather it manually. The data scraped and displayed was stored in a non-relational Mongo database. Additionally, I was able to connect the scraping script so that each time a button was clicked, the scraping occured once again, the database got updated, and new data was displayed. This button only works under the condition that these webpages don't change their HTML components I used for scraping. And lastly, by using Bootstrap's grid system I was able to create a responsive web app that could accomodate to any device people view it from.

## **Resources**
---
### Techniques:
* Python
* Jupyter Notebook
* Pandas, BeautifulSoup, Splinter, ChromeDriverManager, Flask, PyMongo
* MongoDB
* HTML5
* Bootstrap 3

## **Summary**

The Desktop view & Iphone View

![ScreenShot](https://github.com/ruimin1231/Web-Scraping-with-HTML-CSS/blob/main/challenge/images/mission_to_mars_desktop1.png)

![ScreenShot](https://github.com/ruimin1231/Web-Scraping-with-HTML-CSS/blob/main/challenge/images/mission_to_mars_desktop2.png)

Phone view:

![ScreenShot](https://github.com/ruimin1231/Web-Scraping-with-HTML-CSS/blob/main/challenge/images/iPhone_view1.png)

![ScreenShot](https://github.com/ruimin1231/Web-Scraping-with-HTML-CSS/blob/main/challenge/images/iPhone_view_2.png)

The final product was a fully-functional web application creted with Flask that included images, a table with information about Mars in comparison to Earth, and the latest article title and short description scraped from the NASA's webpage. Each time we click on the "Scrape New Data" button new information will be updated on both the website and the MongoDB.

## **Code**
---

* App script: [app.py](path/to/app.py)
* HTML code: [html](path/to/templates)
* Scraping script: [scrapping](path/to/scraping.py)

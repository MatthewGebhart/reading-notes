# Class 17 - Web Scraping

## Reading

### Web Scrape with Python in 4 minutes
[Source Credit](https://towardsdatascience.com/how-to-web-scrape-with-python-in-4-minutes-bc49186a8460)
- Web scraping is a technique to automatically access and extract large amounts of information from a website
- use the inspector to find the source for the data you want. 
- BeautifulSoup lets us parse through the HTML to find what we want
- we can use findAll() method to find all `a` tags for example
- make sure to include code to pause our code so we don't get flagged was a spammer `time.sleep(1)`

### What is Web Scraping?
[Source Credit](https://en.wikipedia.org/wiki/Web_scraping)
- typically refers to automated processes implemented using a bot or web crawler.
- Scraping a web page involves fetching it and extracting from it
- Fetching is the downloading of a page (which a browser does when a user views a page)
- The content of a page may be parsed, searched and reformatted, and its data copied into a spreadsheet or loaded into a database
- common uses are online price change monitoring and price comparison, product review scraping (to watch the competition), gathering real estate listings, weather data monitoring, website change detection, research, tracking online presence and reputation, web mashup, and web data integration.
- methods that some websites use to prevent web scraping, such as detecting and disallowing bots from crawling (viewing) their pages

### How to scrape websites without getting blocked
[Source Credit](https://www.scrapehero.com/how-to-prevent-getting-blacklisted-while-scraping/)
-  web crawlers, scrapers or spiders (words used interchangeably) don’t really drive human website traffic and seemingly affect the performance of the site, some site administrators do not like spiders and try to block their access.
- Basic rule - Be Nice - BE GOOD AND FOLLOW A WEBSITE’S CRAWLING POLICIES
- robot.txt file on a website has specific rules for scraping (respect it)
- Make the crawling slower, do not slam the server, treat websites nicely
- Do not follow the same crawling pattern
- Make requests through Proxies and rotate them as needed
- Rotate User Agents and corresponding HTTP Request Headers between requests


## Videos

### Track Amazon Prices
[Source Credit](https://www.youtube.com/watch?v=Bg9r_yLk7VY)
- good walkthrough of scraping and also sending an email from a python app


## Bookmark and review

[Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/)

## Things I want to know more about
- this is interesting. I'm looking forward to trying it out
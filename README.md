# beautifulsoup-scraping-challenge
Challenge for module 11 for Penn Data &amp; Visualization Bootcamp - Internet Data Scraping using Python and Beautiful Soup

**Part 1**
In part 1 of the challenge, we scrape the site "https://static.bc-edx.com/data/web/mars_news/index.html", which contains various informative articles around Mars and other planets. 

The goal of the scraping is to quickly compile a list of articles and their descriptions that are offered on the, rather than going one by one and copying and pasting the article names and descriptions.

Before scraping the data onsite, you will import dependencies for BeautifulSoup and Splinter, set the browser to chrome, and set the URL. Once onsite, you will use the inspection tool, which can be easily accessed via F12 on your keyboard, to find the div and class names of the articles within the HTML code.

BeautifulSoup allows us to import the data, filtering for article names & descriptions, and parse the HTML code. By creating a list and looping through the parsed HTML, we can get a clean read of the available article names on the websites and their previews/descriptions.

**Part 2**
In part 2 of the challenge, we take a similar approach to scraping web data using Beautiful Soup and Splinter, now extracting from an online table which has daily data on Mars weather & atmospheric pressure.

This data can help us understand how time (rotations around the sun) differ from Earth, how average daily temperatures and atmospheric pressures differ by day and by month. Using this data, we find that about 1800 "Earth Days" (terrestrial days) exist in a Martian Year.

This code also provides the functionality to explort data to a CSV file in your local drive.

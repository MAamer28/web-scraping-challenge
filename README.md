# Module 11: Web Scraping Challenge
Module 11 Challenge

## Background
You’re now ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

As you work on this Challenge, remember that you’re strengthening the same core skills that you’ve been developing until now: collecting data, organizing and storing data, analyzing data, and then visually communicating your insights.

## Data Analysis
In the first part of this challenge, the Mars news site ( https://static.bc-edx.com/data/web/mars_news/index.html) was visited and scraped via Splinter and web elements extracted to form a Soup object. That object was then analyzed further to produce a list of news headlines and text previews on the aforementioned page.

In the second part, Mars temperature and pressure data collected by the Curiosity rover was extracted from the site (https://static.bc-edx.com/data/web/mars_facts/temperature.html). 

A Pandas DataFrame was then created and data munging applied to produce a DataFrame that can be analyzed for further information.

### Temperature on Mars
![Mars_Temp](https://github.com/MAamer28/web-scraping-challenge/assets/130619866/cadc6363-51b4-4fa4-8ae2-0eb60064f760)

On average, the third month is the coldest on Mars with an average of -83.3 C and the eighth month is the warmest with an average of -68.3 C. This is based on the daily minimum temperatures measured by the Curiosity rover over a period of years.

### Pressure on Mars
![Mars_Pressure](https://github.com/MAamer28/web-scraping-challenge/assets/130619866/3a1bd1ff-b3e9-4612-939d-6510ce6996ba)

Atmospheric pressure on Mars is lowest on the sixth month at 745 Pa and highest in ninth month at 913 Pa. 

### Martian Temporal Analysis
![Mars_l](https://github.com/MAamer28/web-scraping-challenge/assets/130619866/bdd478d9-cbf9-4036-9876-162e2f57a44e)

The length of a Martian year in terrestrial days was calculated by plotting the solar longitudes of the Curiosity rover vs. terrestrial dates. The distance in terrestrial days between solar longitude peaks was then calculated to yield 687 terrestrial days in a single Martian year.

## References
- https://static.bc-edx.com/data/web/mars_news/index.html
- https://static.bc-edx.com/data/web/mars_facts/temperature.html

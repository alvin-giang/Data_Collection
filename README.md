# Module11_Challenge
## Data Collection
### Introduction
This challenge I have taken on a full web-scraping and data analysis project. I have learned to identify HTML elements on a page, identify their 'id' and 'class' attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. I have also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage. 
Working on this challenge gives me a chance to strengthen my core skills that I have been developing until now: collecting data, organising and storing data, analysing data, and then visually communicating insights.

### Scrape Titles and Preview Text from Mars News
I have used automated browsing to visit the Mars news site Links to an external site.. Inspect the page to identify which elements to scrape. Then create a Beautiful Soup object and use it to extract text elements from the website. After that, I extract the titles and preview text of the news articles that I scraped, store the scraping results in Pythin data structures (in a Python list).

### Scrape and Analyse Mars Weather Data
In this part, I used automated browsing to visit the Mars Temperature Data Site Links to an external site, then inspect the page to identify which elements to scrape. I create a Beautiful Soup object and use it to scrape the data in the HTML table. After that, I assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. 
I have analysed the dataset by using Pandas functions to answer the following questions:
    1. How many months exist on Mars?
    2. How many Martian (and not Earth) days worth of data exist in the scraped dataset?
    3. What are the coldest and the warmest months on Mars (at the location of Curiosity)?
    4. Which months have the lowest and the highest atmospheric pressure on Mars?
    5. How many terrestrial (Earth) days exist in a Martian year?
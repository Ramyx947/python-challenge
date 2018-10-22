# Soho Strategy Python Challenge (Junior-Level)
Your challenge is to create a scraper which is capable of extracting metadata about datasets listed on the [data.gov.uk](https://data.gov.uk/) website. This data should be stored, and 'interesting' aggregate statistics rendered in-browser in a visual format.

## Requirements
- The scraper should be built using Python.
- The scraper should extract the `Title`, `Publisher`, `Date Last Updated`, `Topic`, and other information available which might be relevant to the datasets listed on [data.gov.uk](https://data.gov.uk/).
- This metadata should be stored locally in a format of your choosing (or in the cloud with a 3rd party scraper-runner platform like [Scrapy Cloud](https://scrapinghub.com/scrapy-cloud), which in many cases may prove simpler and easier).
- You should use a graphing framework to visually display a selection of interesting observations (e.g. the most popular topics, most frequently-appearing words, or update frequency over time) in a user's browser.

## Rules
- **You are free to use any frameworks or libraries you think would help, however for this challenge we recommend Scrapy.**
- You can contact team+codechallenge@sohostrategy.com at any time to discuss the test or ask questions.
- You may use [Plotly](https://plot.ly/python/) or [D3.js](https://d3js.org/) to graph the data you have extracted in some manner.
- It is entirely up to you how much or how little of the scraped metadata you choose to visualise, and in what manner. We are looking for general evidence of an ability to work with data and think appropriately about its usage and display.
- You are welcome to use bootstrapping tools that may help you in this.
- You are not required to style the charts/graphs produced, but feel free add your own basic styles to make them more presentable.

## Comments
You will be judged on the efficiency of your scraper, the quality of your code, and your ability to pick out key data for visualisation. If you have any issues with the test, please get in touch. We're looking for confident use of Python, and an understanding of basic data visualisation principles. Please compile your code so the visual output page works across modern browsers.

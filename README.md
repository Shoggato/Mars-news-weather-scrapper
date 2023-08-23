# Mars-news-weather-scrapper

Table of Contents:

 -[Background](#Background)<br>
 -[Deliverables](#Whats)<br>
 -[Questions](#questions)

# Background
You’re now ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

As you work on this Challenge, remember that you’re strengthening the same core skills that you’ve been developing until now: collecting data, organizing and storing data, analyzing data, and then visually communicating your insights.

# Whats in here?
This new assignment consists of two technical products. You will submit the following deliverables:

Deliverable 1: Scrape titles and preview text from Mars news articles.
![Scrape Preview](/images/deliverable%201%20images/mars_articles_list_preview.png)

Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.
The following DataFrame put together by scraping the HTML titles and excerpts of each article from the website https://static.bc-edx.com/data/web/mars_facts/temperature.html.
![Mars Weather DataFrame](/images/deliverable%202%20images/weather_data_df.png)
![Data Types from weather_mars_df](/images/deliverable%202%20images/weather_data_df_dtypes.png)


This DataFrame was then used to answer the following questions.


# Questions

How many months exist on Mars?
Evidentily there are twelve months on Mars, but they are longer than the months on Earth.

How many Martian (and not Earth) days worth of data exist in the scraped dataset?
There are 1867 days worth of Martian data that has been scraped.

What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
Find the average the minimum daily temperature for all of the months.
Plot the results as a bar chart.
![Minimal Temperatures on the Mars surface near the rover](/images/deliverable%202%20images/mars_month_temperature_bar.png)
The coldest and warmest months on Mars are March (coldest) and August(warmest).  Still they are still pretty fridged.

Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
Find the average the daily atmospheric pressure of all the months.
Plot the results as a bar 
![Mars atmospheric pressure](/images/deliverable%202%20images/mars_month_atmospheric_pressure_bar.png)chart.
The months that have the lowest atmospheric pressure on mars are June, while the highest atmospheric pressure appears to be September.

About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
Consider how many days elapse on Earth in the time that Mars circles the Sun once.
Visually estimate the result by plotting the daily minimum temperature.
![Martian days plotted with minimal temperatures](/images/deliverable%202%20images/mars_days_line.png)
Counting between the first data point starting at zero, and ending at the final data point from eye balling the graph falls somewhere around 680.  So there is about 680 Earth days per one Martian year.  According to google there are 687 Earth days compared to one year on Mars.

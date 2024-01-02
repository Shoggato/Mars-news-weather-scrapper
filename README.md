# RedPlanetExplorer Web Scraper

## Table of Contents:

- [Background](#background)
- [Deliverables](#whats-in-here)
- [Questions](#questions)

## Background

Embark on a comprehensive web-scraping and data analysis project focusing on Mars news articles and weather data. Leverage your skills in automated browsing with Splinter and HTML parsing with Beautiful Soup to collect, organize, analyze, and visually communicate insights from Mars-related information.

## Whats in here?

### Deliverable 1: Mars News Scraper

Scrape titles and preview text from Mars news articles and present them in a structured list.

![Scrape Preview](/images/deliverable%201%20images/mars_articles_list_preview.png)

### Deliverable 2: Mars Weather Analysis

Scrape and analyze Mars weather data from a table. The resulting DataFrame provides insights into Martian atmospheric conditions.

#### Mars Weather DataFrame

![Mars Weather DataFrame](/images/deliverable%202%20images/weather_data_df.png)

#### Data Types from weather_mars_df

![Data Types from weather_mars_df](/images/deliverable%202%20images/weather_data_df_dtypes.png)

### Questions

1. **How many months exist on Mars?**
   - Evidently, there are twelve months on Mars, each longer than Earth months.

2. **How many Martian (and not Earth) days worth of data exist in the scraped dataset?**
   - There are 1867 Martian days worth of data in the scraped dataset.

3. **Coldest and Warmest Months on Mars**
   - Coldest: March
   - Warmest: August
   - Visualization: Bar chart of average minimum temperatures.
   ![Minimal Temperatures on the Mars surface near the rover](/images/deliverable%202%20images/mars_month_temperature_bar.png)

4. **Months with Lowest and Highest Atmospheric Pressure on Mars**
   - Lowest: June
   - Highest: September
   - Visualization: Bar chart of average atmospheric pressure.
   ![Mars atmospheric pressure](/images/deliverable%202%20images/mars_month_atmospheric_pressure_bar.png)

5. **About how many terrestrial (Earth) days exist in a Martian year?**
   - There are approximately 680 Earth days per one Martian year.
   - Visualization: Line chart plotting daily minimum temperatures.
   ![Martian days plotted with minimal temperatures](/images/deliverable%202%20images/mars_days_line.png)

## Usage

1. Ensure Python and required libraries are installed.
2. Run `mars_news_scraper.py` for Mars news scraping.
3. Run `mars_weather_analysis.py` for Martian weather analysis.
4. Explore the exported CSVs in the `Resources/` directory.

## Contributing

Feel free to contribute by opening issues or submitting pull requests. Your input is highly valued!

## License

This project is licensed under the [MIT License](LICENSE).

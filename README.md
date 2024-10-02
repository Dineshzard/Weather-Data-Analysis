# Weather-Data-Analysis
**Weather Data Scraping Project**

**Overview:**

This project involves scraping weather data from Weather.com and extracting detailed weather information. The scraped data includes daily forecasts with various weather parameters for a selected location. The data is structured in a tabular format and saved for further analysis.


**Data Fields**
**The weather data includes the following fields:**

**Date:** The specific date of the weather forecast.
**Day: **The day of the week corresponding to the date.
**High_temperature:** The highest temperature forecasted for the day (in degrees Celsius/Fahrenheit).
**Low_temperature:** The lowest temperature forecasted for the day (in degrees Celsius/Fahrenheit).
**Weather_conditions:** General weather description (e.g., cloudy, sunny, rainy).
**Rain_percentage:** The probability of rain as a percentage.
**Wind_speed:** Wind speed, measured in miles per hour or kilometers per hour.
**Wind_direction:** The direction of the wind (e.g., N, NE, SW).
**Tools and Libraries**
The project was implemented using the following tools and libraries:

**Python:** The core programming language for scraping and data processing.
**BeautifulSoup:** For web scraping and extracting data from the HTML content.
**Pandas:** To clean, structure, and analyze the scraped data.
Project Workflow
Data Scraping: Data was scraped from Weather.com using Python and BeautifulSoup.
Data Cleaning: The extracted data was cleaned and transformed using Pandas to ensure consistency and accuracy.
Data Saving: The cleaned data was saved in CSV format for further analysis.

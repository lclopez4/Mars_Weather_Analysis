Mars Weather Data Analysis
This project analyzes daily Martian weather data collected at the Curiosity rover’s location. The dataset includes variables such as minimum daily temperature, atmospheric pressure, and terrestrial date. Using Python, BeautifulSoup, Selenium, and Pandas, the data was scraped, cleaned, and prepared for visual and statistical analysis.

Tools Used

Python

Pandas

BeautifulSoup

Selenium with webdriver-manager

Matplotlib

Jupyter Notebook

GitHub Copilot and ChatGPT (used to help fix environmental errors, troubleshoot code issues, and refine syntax)

Data Preparation

The data was scraped from an HTML table and parsed into a structured list of rows.

A Pandas DataFrame was created using extracted row data and column headers.

Data types were cleaned and converted:

terrestrial_date → datetime

sol, ls, month → integer

min_temp, pressure → float

Key Analyses

Minimum Temperature Trends

Calculated average minimum temperature for each Martian month.

Identified the coldest and warmest months.

Visualized seasonal variation using a bar chart.

Atmospheric Pressure Patterns

Calculated average atmospheric pressure by month.

Identified the lowest and highest pressure months.

Presented data in a uniform bar chart for easy comparison.

Martian Year Estimation

Graphed minimum daily temperatures over time using Earth dates.

Estimated a Martian year to span ~670–690 Earth days based on recurring temperature cycles.

Confirmed alignment with known Martian year length of ~687 Earth days.

Output

Cleaned dataset saved as: mars_weather_data.csv

Visualizations created using Matplotlib

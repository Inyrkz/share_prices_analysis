# share_prices_analysis
Extracting financial data of various corporations from multiple sources and analyzing the data.

I just completed an exhilarating project as a Data Scientist / Data Analyst for a hypothetical startup investment firm that helps customers invest their money in stocks 📈. This project is part of the @IBM [Python Project for Data Science course](https://www.coursera.org/learn/python-project-for-data-science/home/welcome) on @Coursera.

My job was to extract financial data like historical share prices and quarterly revenue reportings from various sources using Python libraries and web scraping on popular stocks like Tesla, Amazon, AMD, and GameStop 📊.


In Phase 1, I used the yfinance API to extract historical stock data of Apple and Advanced Micro Devices (AMD). It wasn't all smooth sailing! Not all stock data is available through an API, so I had to get creative and use web scraping to obtain some data 😎. The notebook is [here](https://github.com/Inyrkz/share_prices_analysis/blob/main/extract_api.ipynb).





![Open Share Price of Apple Stock]((https://github.com/Inyrkz/share_prices_analysis/blob/main/resources/open%20share%20price%20of%20apple%20stock%20api.PNG?raw=true)
*Open Share Price of Apple Stock*





![Apple Stock Dividend Line Chart](https://github.com/Inyrkz/share_prices_analysis/blob/main/resources/apple%20stock%20dividend%20api.PNG?raw=true)

*Apple Stock Dividend Line Chart*




In Phase 2, I utilized web-scraping techniques to obtain Netflix and Amazon stock data, where I learned a cool way to extract tables from a web page directly into a DataFrame using BeautifulSoup and the read_html() function of Pandas. The notebook is [here](https://github.com/Inyrkz/share_prices_analysis/blob/main/webscraping.ipynb).



![Netflix Stock Data](https://github.com/Inyrkz/share_prices_analysis/blob/main/resources/netflix%20data%20phase%202.PNG)

*Netflix Stock Data*



![Scrape Netflix Data](/resources/scrape netflix data.PNG)

*Scrape Netflix Data*




In the final phase of the project (Phase 3), I brought everything together. I extracted the profit data for Tesla and GameStop and built a dashboard to compare the stock price vs the profit for a hedge fund. I used the yfinance API to extract Tesla and GameStop (GME) stock data and used web scraping to Extract Tesla and GME Revenue Data. I plotted the Tesla and GameStop stock graphs using the Plotly library.The notebook is [here](https://github.com/Inyrkz/share_prices_analysis/blob/main/Final%20Assignment.ipynb).

![GME Stock Data Extraction](/resources/q3 yup.PNG)

*GME Stock Data Extraction*



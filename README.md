# Portfolio-Construction-Practice
p1: Web Scraping Data -> MoM strategy
  1.1 I used what wikipedia said the component stocks of SP500 through the website:https://en.wikipedia.org/wiki/List_of_S%26P_500_companies,and return the name ticker name of the 503 stocks
  1.2 With the ticker names obtained at 1.1, I download the stock data via Yahoo Finance API through Python, the data downloaded was mainly the closing price from 01.01,2019 to 30.12.2019. 4 stocks closing prices were missing at the given period:CARR; CEG; OGN; OTIS as their closing price was not available that time time.
  1.3 Load all downloaded data into one single pd.dataframe like:
  <img width="1028" alt="image" src="https://user-images.githubusercontent.com/105639985/198839263-020812a4-7e43-4370-bcb9-c6a53d8a4c16.png">

p2: Autoregression Model set up at 5% significance level -> Portfolio construction in the sample(8 months) -> Portfolio Testing out of Sample(4 months)

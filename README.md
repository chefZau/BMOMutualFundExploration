# Exploring BMO Mutual Funds
## by Luca Zhou

Investment is a field that requires lifelong learning, and I'd like to start earlier. The primary purpose of this project is to explore all BMO mutual funds performances data using **Jupyter Notebook** and build a stable portfolio for my future financial independence. This project consists of three parts:

1. **Data wrangling**: collect and clean the data into a playable format. If you wonder how the data collection and cleaning is done, see [`DataWrangling.ipynb`](https://github.com/chefZau/Exploring-BMO-MFunds/blob/main/DataWrangling.ipynb) for more detail.
2. **Exploratory data analysis (EDA)**: supplement statistics with appropriate plots to understand the distributions and relationships. Notice that the file [`EDA.ipynb`](https://github.com/chefZau/Exploring-BMO-MFunds/blob/main/EDA.ipynb) contains the detailed exploration process.
3. **Communicate my findings**: implement a dynamic dashboard for communicating insights.

## Prerequisite

The project was built using **Python 3**, and the primary IDE is **Jupyter Notebook**. To follow along, I recommend installing the [Anaconda](https://docs.anaconda.com/anaconda/install/index.html) distribution since it includes all necessary Python libraries and Jupyter Notebook. The following libraries are expected to be used in this project:

* NumPy
* Pandas
* Matplotlib
* Seaborn

Notice that in the data wrangling section, web scraping is needed. Here are the essential libraries I used for extracting and parsing web data:

* [Requests](https://docs.python-requests.org/en/master/): a HTTP library for making requests.
* [Selenium](https://selenium-python.readthedocs.io): create a browser and act like a human. (make sure you download the driver)
* [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/): for pulling data out of HTML and XML files.

## Dataset

Since I don't have first-hand data from BMO, web scraping is needed. To know more about how I collected the data, see [`DataWrangling.ipynb`](https://github.com/chefZau/Exploring-BMO-MFunds/blob/main/DataWrangling.ipynb) for more detail.

The following are the cleaned datasets I wrangled from BMO:

| File Name | Definition |
| ------------- |:-------------:|
|[`resources/BMOMutualFunds.csv`](https://github.com/chefZau/Exploring-BMO-MFunds/blob/main/resources/BMOMutualFunds.csv)|It includes basic information about individual funds.|
|[`resources/BMOFundPrices.csv`](https://github.com/chefZau/Exploring-BMO-MFunds/blob/main/resources/BMOFundPrices.csv)|It provides information about the fund price for a given date in the past 12 months.|

The features (columns) included in the data are as follows:

**`resources/BMOMutualFunds.csv`**

| Feature       | Definition    |
| ------------- |:-------------:|
| Fund ID | the BMO fund ID |
| Fund Name | the name of the fund |
| Asset Class | the asset class of the fund |
| Assets | the assets of the fund (million) |
| Date Started | the created date |

**`resources/BMOFundPrices.csv`**

| Feature       | Definition    |
| ------------- |:-------------:|
| Fund ID | the BMO fund ID |
| Effective Date | the date of the record |
| NAV | net asset value |
| Income ||
| Capital Gain ||
| Total Distribution ||
| Reinvestment Price ||


## Summary of Findings


## Key Insights for Presentation


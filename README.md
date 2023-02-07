## Top Data Analytics Companies
To improve effectiveness in business processes, companies are focussing on collecting and utilizing data. Data analytics companies enable businesses to analyze the acquired data and use them as required. Data analytics services can assist in product development, identifying potential market gaps, improving operational efficiency, etc.

Project 1 is about webscaping information about top data Analytics company from the website [Good Firm](https://www.goodfirms.co/big-data-analytics/data-analytics)

The aim of this project is to get details about top data analytics company. These details includes, review, rating, year founded, location, etc.

[View Notebook](https://nbviewer.org/github/Jhaniee/Top-data-analysis-company-web-scrape/blob/main/Project%201.ipynb)

### Summary

![](newplot(7).png)

* The webpage from Goodfirm was succesfully accessed and downloaded using Request library. 
* BeautifulSoup was used to locate and extract the details from the downloaded html file
* The extracted details was converted to data frame using Pandas.
* The file was cleaned 
* EDA as performed on the cleaned file for some insights.

#### Findings
* About 30 firms are rated 5 star while 12 are rated between 4.8 - 4.9
* Very few firms (3) has a review above 30
* Most of the firms are located in United States followed by India.
# HK-IPO-Analysis
An open business environment and sound legal system makes Hong Kong an ideal place for initial public offering (IPO). Many HK securities firms have been offering zero subscription fee with low margin loan rate which attracted huge response from investors to subscribe for IPO shares with loan. Some people believe IPO is a good way to earn “easy money” and the market hype is the best indicator of the return.

The objective of this notebook is to analyze Hong Kong IPO return by answering questions like:	How does over subscription rate relate to percentage return on list day? How often do the stock prices increase on list day? If we subcribe every IPO for the past few years, what would be the average expected return?

In this notebook, I scraped IPO data (recent 2 years) from AASTOCKS and performed exploratory data analysis by using BeautifulSoup and pandas. 

Based on the result, assuming transaction fee/commission is zero, it is quite likely that we can earn small amount of “easy money” if we keep subscribing the IPO. In the future, I may include more data such as market capitalization and lot size and see if I can build a predictive model for the return on list day. 


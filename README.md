# Analzying Brand Sponsorship Impact on Sales
### Estimating the Counterfactual

This repo houses code for a brand analytics project utilizing dummy data generated for a fictional product for Brand A.

# Overview
For the past several years, Brand A has sponsored Event X. There are several possible benefits from this investment:

* An immediate boost in sales around the time of Event X
* A long-term boost in sales due to increased growth over time
* Preventing other brands from becoming the official sponsor
* An increase in name brand recognition and brand equity (potentially translating into long-term growth)

While long-term growth is the most important outcome, it is also the hardest to quantify because when we are looking at yearly volume growth Event X is only one of many drivers of growth. This analysis focuses on what we can quantify, which is the short-term return on Brand A's sponsorship of Event X.

The estimates provided are the size of sales increase around Event X, in which we show that it is reasonable to assume increase is caused by marketing activity during that time period. Currently, we are not able to distinguish among the various forms of promotion that occur. As such, we are not able to determine what are the relative impacts of advertising around Event X v. direct sponsorship. However, we can estimate the short-term sales impact of Event X activity as a whole by isolating Event X **incremental volume**. We will further explain the methodology next.


# Method
## Estimating The Counterfactual
* First, we will isolate Event X incremental volume. We know how many cases of Brand A were sold during Event X for the last three years (using takeaway data from Nielsen and NABCA). The main goal of the analysis is to produce a quality estimate of how many cases we would have sold if we had not sponsored Event X. The difference between how many cases we actually sold and how many cases we would have sold if we had not sponsored Event X is the best way to quantify the impact of Event X on short-term sales.

* Second, we check that factors such as price and distribution are not impacting the sales during Event X. After this, we calculate an **ROI range** with high- and low-end assumptions. This will be further explained in the section **“Figuring out the ROI.”**

* Finally, in addition to volume and financial data, we also explore **Google Trends** data to show how search interest is trending over time for Brand A vs competitor brands (Brand B, Brand C, and Brand D).

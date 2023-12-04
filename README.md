# Regression
# Hotel Booking Analysis
### Access the data here:

https://drive.google.com/file/d/1m52m3uiXXbHO6A8Lq0-R5AS9wkK6ZBXM/view?usp=sharing
https://drive.google.com/file/d/1tTE8zgF5vBCbcFrHfUgpf8i1B0xcZlpG/view?usp=sharing


In this notebook, we delve into the dynamic world of Rossmann stores, a retail giant operating over 3,000 drug stores across 7 European countries. Our primary objective is to harness the power of regression analysis to accurately predict the sales figures of Rossmann stores. The journey begins with a comprehensive exploration of the dataset through Exploratory Data Analysis. Insights gained from this step lay the foundation for subsequent analyses. Visualizations and statistical summaries unveil patterns, outliers, and potential relationships within the data. To decipher the temporal nuances of Rossmann's business, we employ Exponential Moving Averages. This technique allows us to dissect trends and seasonality trends, providing valuable context for our predictive models.

### Guide to Dataset features:

Rossmann Stores Data.csv - historical data including Sales

store.csv - supplemental information about the store

Data fields Most of the fields are self-explanatory. The following are descriptions for those that aren't.

Id - an Id that represents a (Store, Date) duple within the test set

Store - a unique Id for each store

Sales- the turnover for any given day (this is what you are predicting)

Customers - the number of customers on a given day

Open - an indicator for whether the store was open: 0 = closed, 1 = open StateHoliday - indicates a state holiday. Normally all stores, with few exceptions, are closed on state holidays. Note that all schools are closed on public holidays and weekends. a = public holiday, b = Easter holiday, c = Christmas, 0 = None

SchoolHoliday - indicates if the (Store, Date) was affected by the closure of public schools

StoreType - differentiates between 4 different store models: a, b, c, d

Assortment - describes an assortment level: a = basic, b = extra, c = extended

CompetitionDistance - distance in meters to the nearest competitor store

CompetitionOpenSince[Month/Year]- gives the approximate year and month of the time the nearest competitor was opened

Promo - indicates whether a store is running a promo on that day

Promo2 - Promo2 is a continuing and consecutive promotion for some stores: 0 = store is not participating, 1 = store is participating

Promo2Since[Year/Week] - describes the year and calendar week when the store started participating in Promo2

PromoInterval - describes the consecutive intervals Promo2 is started, naming the months the promotion is started anew. E.g. "Feb,May,Aug,Nov" means each round starts in February, May, August, November of any given year for that store


## Regression Analysis:

Diving into the heart of predictive modelling, we explore various regression algorithms:

Linear Regression Analysis: A classic approach assuming a linear relationship between variables.

Regularized Regression Analysis (Lasso, Ridge, Elastic Net): Techniques to combat overfitting and enhance model robustness.

Decision Tree Analysis: Leveraging tree-based structures to capture non-linear patterns in the data.

Random Forest Regression Analysis: Harnessing the power of ensemble learning to improve predictive accuracy.

In comparison, surpassing its counterparts, the Random Forest algorithm emerges as the star performer, boasting an impressive 92% accuracy in predicting Rossmann store sales.

## Conclusion and Future Work:

In conclusion, our regression analysis paints a vivid picture of Rossmann store sales prediction. We highlight key findings, discuss algorithmic strengths and limitations, and propose avenues for future enhancement. This journey not only offers insights into the dynamics of retail sales but also sets the stage for further exploration and refinement of predictive models.

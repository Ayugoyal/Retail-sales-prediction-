# Retail-sales-prediction-
Retail sales prediction

●	Id - an Id that represents a (Store, Date) duple within the test set
●	Store - a unique Id for each store
●	Sales - the turnover for any given day (this is what you are predicting)
●	Customers - the number of customers on a given day
●	Open - an indicator for whether the store was open: 0 = closed, 1 = open
●	StateHoliday - indicates a state holiday. Normally all stores, with few exceptions, are closed on state holidays. Note that all schools are closed on public holidays and weekends. a = public holiday, b = Easter holiday, c = Christmas, 0 = None
●	SchoolHoliday - indicates if the (Store, Date) was affected by the closure of public schools
●	StoreType - differentiates between 4 different store models: a, b, c, d
●	Assortment - describes an assortment level: a = basic, b = extra, c = extended
●	CompetitionDistance - distance in meters to the nearest competitor store
●	CompetitionOpenSince[Month/Year] - gives the approximate year and month of the time the nearest competitor has opened
●	Promo - indicates whether a store is running a promo on that day
●	Promo2 - Promo2 is a continuing and consecutive promotion for some stores: 0 = store is not participating, 1 = store is participating
●	Promo2Since[Year/Week] - describes the year and calendar week when the store started participating in Promo2
●	PromoInterval - describes the consecutive intervals Promo2 is started, naming the months the promotion is started anew. E.g. "Feb, May, Aug, Nov" means each round starts in February, May, August, and November of any given year for that store


The data was huge and some of the column were not needed so we drop it from the data.
The cleaning data was done and created the new cleaned data frame consists of the column were compared to gain the knowledge for the prediction.  Worked individually gaining same insights doing some EDA .

•	In the Rossmann sales prediction project there is a dataset which contains sales information
•	The sales column contain172817rows with 0 sale. So we created a new data frame in which we removed 0 sales rows and tried train our model we used various algorithms and got accuracy score around 74%
•	The total dataset sale =0 rows . So we trained and another model using various algorithms accuracy near about 92%which is far better than previous model.
•	The removing sales =0 rows actually removes lot of information from dataset as it has 172817rows which is quite large 
•	**Rossmann Sales Dataset** - This dataset is a live dataset of Rossmann Stores. On analysing this problem we observe that rossmann problem is a regression problem and our primarily goal is to predict the sales figures of Rossmann problem. In this Notebook we work on following topics Analysing the dataset by using Exploratory Data Analysis using exponential moving averages analyse trends and seasonality in Rossmann dataset Analyse Regression using following prediction analysis. A) Linear Regression Analysis B)Elastic Regression (Lasso & Ridge Regression). C) Dession tree and random  forest  regression   and random forest Regression

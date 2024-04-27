# Solar-cycle-prediction
In this study, I have presented Random Forest, XGBoost, Light GBM, Histogram Gradient Boosting, Ridge regression models using python to forecast the 25 and 26th solar cycle using the monthly sunspot area (SSA) data from the Royal Observatory, Greenwich (RGO) USAF/NOAA during the period of May 1874 to April 2023(149 years).
![image](https://github.com/Souvik2biswas/Solar-cycle-prediction/assets/47652348/9503fad8-9007-4843-99e9-7d6d74e3806d)
Method	Train-Test Split	Window Size	R2 Score	MAPE	RMSE	Peak	Time
Random Forest	1874-2008:2008-2023	96	0.7566	0.5847	173.42	1736.49	Jun-24
	1874-2018:2018-2033	96	0.9938	0.0494	18.33	911.45	Jul-36
XGBOOST	1874-2008:2008-2023	96	0.7121	0.6167	180.53	1587.82	May-24
	1874-2018:2018-2033	96	0.9848	0.0683	24.06	907.08	Aug-36
Light Gradient Boosting Machine	1874-2008:2008-2023	96	0.7381	0.6485	173.69	1527.49	Apr-24
	1874-2018:2018-2033	96	0.9276	0.1843	48.10	959.61	Jun-36
Ridge Regression	1874-2008:2008-2023	96	0.6374	7.4531	194.93	1356.98	May-24
	1874-2018:2018-2033	96	0.9993	0.0085	5.69	1241.58	Sep-34
Histogram Gradient Boosting	1874-2008:2008-2023	96	0.7397	0.6194	173.39	1793.89	Apr-24
	1874-2018:2018-2033	96	0.9814	0.0598	21.34	896.35	Dec-39

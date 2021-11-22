This is a Course Project for FA21: I535 Management, Access, Use of Big Data.
My project title is "Bike Sharing Demand Prediction with Python and PySpark". The dataset I used for this project is from https://archive.ics.uci.edu/ml/datasets/bike+sharing+dataset. This dataset contains the Capital bike sharing data between 2011 and 2012 (original source: http://capitalbikeshare.com/system-data) as well as the corresponding holiday schedule (http://dchr.dc.gov/page/holiday-schedule), weather and seasonal information (http://www.freemeteo.com). There are two separate csv files saving in the dataset. One is named as "day.csv", presenting daily based bike rental information. The other file is "hour.csv", presenting hourly based rental information. One of the objectives is to predict the bike rental count on hourly basis using a series of important features as presented in the dataset. Hence, this is a regression problem. The results may help improving the bike sharing system management and services.

Another objective is to compare the process and results with Python and PySpark. Two machine learning models, including simple linear regression and decision trees, were constructed in both Python and PySpark analysis. I mainly applied the knowledge of virtualization, data lifecycle & pipeline as well as distributed processing I have learned from this class for the project. A virtual machine is created on JetStream (https://jetstream-cloud.org/). The whole data lifecycle and pipeline from data integration to publication is detailed illustrated in the main body of the project based on the USGS model. The results are finally published to github.# I535FA21BIGDATAFP

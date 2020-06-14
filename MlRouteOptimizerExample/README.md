**Project:** Optimizing Travel Itineraries With Machine Learning


**Source** https://github.com/vlazovskiy/route-optimizer-machine-learning


**Project goal.** The goal of my project is to optimize travel routes for a delivery vehicle by using machine learning model predictions. This is a two-component problem: first, I train a machine learning model on the data to predict how long it will take a delivery vehicle to go from point one point to another, and I feed these predictions into a genetic algorithm which decides which is the most time efficient visit order for a given set of points. 

Here is an illustration of my pipeline: data -> machine learning -> optimization with genetic algorithm


**Data and Features.** New York City taxi data set was taken from [here](http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml), with an additional New York City weather dataset obtained from [Kaggle](https://www.kaggle.com/cabaki/knycmetars2016).

**Data and Features Objective** Switch New York City taxi data for Brazil most common and problematic routes data (collect the dataset) used by truck drivers. Then Adapt the model for our specific case 

**Models.** The model used is XGBoost to accomodate the more complex numeric and categorical features needed. Is also used a LightGBM model with thoughts regarding the weather data(which might not be relevant for truck drivers and after a experimental test could be taken off)

**Optimization.** For any given set of locations, these location are fed to the machine learning model, which predicts how long it will take to travel between each two given points. Then the algorithm "evolves" to find the visit order which minimizes time spent in transit. 

**Results.** The dataset need to be collect before any result for adequating to hackaton CCR.

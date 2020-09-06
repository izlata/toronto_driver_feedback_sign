# “Watch Your Speed” Driver feedback sign #627 in school safety zone (Toronto): Data analysis and ML models


The Watch Your Speed Program (WYSP) uses devices called driver feedback signs which contain a radar device and an LED display. The radar measures the speeds of oncoming vehicles and the LED sign displays their speeds to the passing motorists, thereby reminding them to check their speeds and to obey speed limits. The City of Toronto’s permanent units are installed in Safety Zones.

## Project

1. Explore the data recorded by the driver feedback sign # 627 (approximate address - 227 Mill Road, Toronto; southbound direction of travel; speed limit - 40 km/hr). The data was collected from January 1, 2019 to February 20, 2020.
2. Train different regression models for predicting an hourly count of vehicles traveling at a speed in the “40 km/hr and higher” speed range for this location (using scikit-learn). The Polynomial Regression model (degree=2) produced the best performance.

Analysis of recorded data and the model can be useful for understanding the situation with safety in this school zone and for planning measures to improve it.

## Data

The datasets were published by Transportation Services on the City of Toronto Open Data Portal.

1.	**“School Safety Zone Watch Your Speed Program – Detailed Speed Counts”** 
An hourly aggregation of observed speeds for each location where a Watch Your Speed Program Sign was installed in 5 km/hr speed range increments.
https://open.toronto.ca/dataset/school-safety-zone-watch-your-speed-program-detailed-speed-counts/
2.	 **“School Safety Zone Watch Your Speed Program – Locations”**
The locations and operating parameters for each location where a permanent Watch Your Speed Program Sign was installed. 
https://open.toronto.ca/dataset/school-safety-zone-watch-your-speed-program-locations/

### The project includes two Jupyter notebooks:

•	Notebook 1 - Download, prepare and explore the data (wysp_sign627_notebook1_analysis.ipynb)

•	Notebook 2 - Data transformation, model training and evaluation (wysp_sign627_notebook2_models.ipynb)

The data will be downloaded, extracted and read into pandas DataFrames when running the Notebook 1.

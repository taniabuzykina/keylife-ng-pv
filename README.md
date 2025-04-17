# keylife-ng-pv
This project uses the data on temperature, humidity, PH and brigtness from NG and PV sensors

The project is split into two parts, based on the provided 2 datasets. 

1. Post-harvest plant dataset - machine learning
<br>Includes the data on produce leaf size, plant height, total energy consumption, disease occurence etc. and __marketable yield__, which was identified as a target variable. In total we have had 20 data entries (10 for solar and 10 for grid), and 18 different measurements. This made the dataset challenging to use for modelling in its original state. 
The idea was to use the provided dataset and collected features to predict marketable yield. However many of the features are as much of measured outcome as the target value. Hence further investigation into the provided features is to be conducted. 

2. Data from vertical farm sensors 
<br>Includes data collected at intervals in the month when the plants are grown. The data contains timestamp, brightness, EC, humidity, ph and temperature(C) both from samples lit by solar panels and grid. Number of entries is not determined yet but is potentially more than 100. 
The plan was to use the image data from CCTV feed and map with the timestamps and sensory data, and use the green coverage % as target value - to build a model that uses sensory input data as features. 


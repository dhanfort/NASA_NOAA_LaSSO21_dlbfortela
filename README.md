# Applying Deep Learning for Prediction of Shoreline Dynamics in Coastal Louisiana
Dhan Lord B. Fortela, PhD (Principal Investigator); Chemical Engineering, University of Louisiana at Lafayette; Email: dhanlord.fortela@louisiana.edu; Office phone: (+1)337-482-5765.

Kevin Toups (Funded Undergraduate Student); Chemical Engineering, University of Louisiana at Lafayette

## 
This LaSSO research project is funded by the partnership grant of Louisiana Space Grant Consortium (LaSPACE) & Louisiana Sea Grant (LSG)

Primary Grant by U.S. Department of Commerce‐NOAA: NA18OAR4170098

Subaward: PO‐0000064084

Louisiana State University

##

This is the online repository for the Data Management Plan of the LaSSO 2021-22 research project. 

The Convolutional Long-Short Term Memory (ConvLSTM) is used to capture the spatio-temporal dynamics of the shoreline changes. ConvLSTM was implemented through the TensorFlow libraries via Keras API in Python. The Jupyter Notebook for the work is included in this repo. The input tensor consists of (1) geo-raster of land-water classfication, (2) precipitation, and (3) temperature. The baseline date is 26 January 1985.


Shown below: Locations of the 25 shoreline study areas used to collect samples of geo-raster data around Marsh Island over time to capture shoreline dynamics. Each study area is 109 pixels (width) by 100 pixels (height). Given that each geo-raster pixel is 30m x 30 m, each study area covers 3,270 meters by 3,000 meters. Data preparation starts with the 4-5-3 raster signal bands (A) that are used in a classification algorithm with the SCP plug-in in QGIS to classify each pixel as either land or water (B). This particular sample geo-raster dataset is the baseline date of 26 January 1985, which is the earliest high-quality Landsat dataset available.


![LaSSO_QGIS_Areas_Classification_Schematic](https://user-images.githubusercontent.com/65507260/175828035-ad06c060-7bb0-49ab-89c5-7f4de033ac3c.jpg)

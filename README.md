# Velib data project
The project is devoted to velib data.
Launch notebooks in R and Python are available at plmlab.math.cnrs.fr/wikistat/Exploration/Velib.
# Description and Aim
The data are loading profiles of the bike stations over one week, collected every hour, from the period of Monday 2nd September to Sunday 7th September, 2014. The loading profile of a station, or simply loading, is defined as the ratio of number of available bikes divided by the number of bike docks.
A loading of 1 means that the station is fully loaded, i.e. all bikes are available.
A loading of 0 means that the station is empty, i.e. all bikes have been rent.
From the viewpoint of data analysis, the individuals are the stations. The variables are the 168 time steps (hours in the week).
The aim is to detect clusters in the data, corresponding to common customer usages. This clustering should then be used to predict the loading profile.

# Guidelines
Descriptive statistics.
PCA to reduce dimension (originally > 150).
Clustering on original data, on PCA coordinates. Other ideas : kernel PCA, coefficients of a suitable functional basis...
Interpretation, comparison.
Timing

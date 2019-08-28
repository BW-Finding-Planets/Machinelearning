Basic workflow: 
Get TCE data from TESS bulk downloads page, use lightkurve api to get the lightcurves corresponding to them, use astropy to process and fold the lightcurves. 
Use astropy and the MAST api to get further information about the stars. 
Run a neural network trained on Kepler data on TESS lightcurve data (processed to be in the same format as the Kepler data) 

Useful links:
https://docs.lightkurve.org/api/index.html
https://github.com/spacetelescope/notebooks/tree/master/notebooks/MAST/TESS
https://archive.stsci.edu/tess/
https://www.kaggle.com/keplersmachines/kepler-labelled-time-series-data
https://astropy-timeseries.readthedocs.io/en/latest/timeseries/
https://github.com/gabrielgarza/exoplanet-deep-learning
https://github.com/elopezaguilera/exoplanets

Special thanks to Joe Bender for his help and lending code.

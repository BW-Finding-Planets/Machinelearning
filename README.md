Basic workflow: <br />
Get TCE data from TESS bulk downloads page, use lightkurve api to get the lightcurves corresponding to them, use astropy to process and fold the lightcurves. <br />
Use astropy and the MAST api to get further information about the stars. <br />
Run a neural network trained on Kepler data on TESS lightcurve data (processed to be in the same format as the Kepler data) <br /><br />

Useful links:<br />
https://mast.stsci.edu/api/v0/_services.html <br />
https://mast.stsci.edu/api/v0/_t_i_cfields.html <br />
https://docs.lightkurve.org/api/index.html <br />
https://github.com/spacetelescope/notebooks/tree/master/notebooks/MAST/TESS <br />
https://archive.stsci.edu/tess/ <br />
https://www.kaggle.com/keplersmachines/kepler-labelled-time-series-data <br />
https://astropy-timeseries.readthedocs.io/en/latest/timeseries/ <br />
https://github.com/gabrielgarza/exoplanet-deep-learning <br />
https://github.com/elopezaguilera/exoplanets <br /><br />

Special thanks to Joe Bender for his help and lending code.

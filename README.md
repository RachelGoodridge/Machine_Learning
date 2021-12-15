## Potentially Hazardous Asteroids
By: Rachel Goodridge

## Abstract
Near-Earth Objects (NEOs), such as asteroids, occasionally have the potential to collide with Earth and cause enormous damage. NASA has been documenting these NEOs as well as many other types of space-going debris and developing diversion tactics given the event of an impact threat. From [NASA’s Small-Body Database](https://ssd.jpl.nasa.gov/tools/sbdb_query.html), information about asteroids was used to predict which are potentially hazardous. Following oversampling to address class imbalance and optimization of many parameters, the best model based on F1 validation scores was XGBoost Classifier. The score on the holdout data was 0.784 and the most important features were absolute magnitude, closest distance to the sun, and orbit uncertainty.

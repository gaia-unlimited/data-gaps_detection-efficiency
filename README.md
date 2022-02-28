# Data taking gaps and detection efficiencies

**This repository is currently under development and it is not ready to use.**

Set of notebooks to estimate the period of times where *Gaia* was not taking data, or the data taken was not used for the different releases, and compute the detection efficiencies as a function of G magnitude and time.

Work based on the "Completeness of the GaiaVerse" ([website](https://www.gaiaverse.space/), [github](https://github.com/gaiaverse)).

## Files in repository

- [match_observations_detections.ipynb](match_observations_detections.ipynb): Using a scanning law, and a time series of individual star measurements, match the observations (predicted by the scanning law) to detections (published measurements).

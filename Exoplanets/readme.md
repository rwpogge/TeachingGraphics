# Exoplanet Properties

Plot exoplanet properties.

These notebooks use `astroquery` to retrieve the most recent data for
confirmed exoplanets from the [NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/).  We include additional data files with basic data for
selected solar system bodies and main sequence stars.

## Notebooks

 * `exoplanet_props.ipynb` - plot various properties for confirmed exoplanets to date:
   - mass vs. orbital semimajor axis
   - radius vs. year of discovery
   - eccentricity vs. orbital period
  
 * `rvHistory.ipynb` - plots of RV semi-amplitude and planet mass vs. discovery year for confirmed RV exoplanets

 * `MassRadius_SSExoStars.ipynb` - Mass-radius relation plot following Chen & Kipping [2017, ApJ, 834, 17](https://ui.adsabs.harvard.edu/abs/2017ApJ...834...17C), Figure 3

# Astronomy Teaching Graphics
Jupyter notebooks and code to create astronomy teaching graphics for all levels from gen-ed to graduate courses

A work in progress, I started migrating my many folders of graphics into a single repository in Spring 2025.  
I've developed a uniform style for the graphics notebook coding based on my experience creating the graphics
for the Ohio State Astrophysics Series of graduate textbooks for Cambridge University Press.

Uses Jupyter and Python with `matplotlib` for creating the graphics

## Graphics Collections

### AtmosTrans

Near- and Mid-Infrared atmospheric transmission.  Based on ATRAN model calculations, useful for illustrating atmospheric infrared absorption.

### Atmosphere

Plots of atmospheric CO2 and CH4 concentrations, global temperature anomaly, and mean sealevel trends from NOAA and NASA public databases. 

### Exoplanets

Exoplanet properties plots.  Uses `astroquery` to retrieve the latest data from the [NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/).

### HumanEye

Plots the photopic (normal) and scotopic (dark-adapted) quantum efficiency
of the human eye.

### MaxwellBoltzmann

Plots demonstrating the Maxwell-Boltzmann distribution for gasses and Jeans Escape.

### Nuclear Fusion

Plots illustrating principles of nuclear fusion in stars.  Includes plots of the curve of nuclear binding energy, the Gamow peak for hydrogen (Boltzmann vs. tunneling), and solar fusion energy generation (p-p and CNO).

### ProperMotions

Proper motion and parallax animations using `astroquery` to retrieve astrometric data from the Gaia DR3 database. The parallax GIF animations are
based on Eric Tollerud's demo notebooks of Gaia DR3 queries, modified to show particular features relevant for 2nd-year astrophysics but also nice
to show gen-ed ("Astro101") courses.

Also has a notebook that uses Gaia and Hipparcos data to plot motions of the stars in the direction of the Big Dipper asterism, and create still frames
ready to be combined into an animation of that motion using tools like `ffmpeg`.

### Romer_SpeedOfLight

Plot the relative positions of the Earth and Jupiter during observations by Ole Roemer of eclipses of Io in the 1670s that demonstrated the finite speed of light.  This is the real data, not the contrived opposition-vs-conjunction plots usually shown in textbooks.

### SolarSystem

Views of the solar system. Uses `astroquery` to retrieve orbit data from the JPL Horizons system for major bodies and the Minor Planet Center orbit
database (MPCORB) for asteroids, TNOs, Centaurs, and comets.  Code in the notebooks solves Kepler's equations numerically to compute positions and
full orbits in XYZ ecliptic coordinates to make plots of the appearance of the solar system.

### Spaceflight

Graphics related to spaceflight orbits.  First entries are the gravity-assist trajectories of Voyager 1 and 2, and an illustration of the Voyager 2 gravity assist by Saturn.  Used for teaching 2nd year astrophysics, uses the trajectories of the spacecraft from the JPL Horizons database, not idealized examples.

### Stars

Stellar spectral classification, luminosity classification, M-R-L relations, 
colors, and effective temperatures.

### TimeKeeping

Graphics related to time-keeping and calendars.  First entry is solar vs. clock time and sunrise/sunset times from
a location on the earth (illustrates the equation of time and relation of local sunrise/sunset times to equinoxes,
solstices, and ap/perihelion).

## Dependencies

Written and tested with Python 3.12 (Anaconda distro), using the following packages.
 * `matplotlib` version 3.9.2
 * `numpy` version 1.26.4
 * `astropy` version 7.0
 * `astroquery` version 0.4.9
 * `scipy` version 1.13.1 (various numerical solvers)
 * `pandas` version 2.2.2
 * `astroplan` version 0.10.1
 

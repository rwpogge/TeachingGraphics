# Astronomy Teaching Graphics
Jupyter notebooks and code to create astronomy teaching graphics for all levels from gen-ed to graduate courses

Just starting out migrating my many folders with many graphics into a single repository, and developing a uniform
style for the graphics.

Uses Jupyter and Python with `matplotlib` for creating the graphics

## Graphics Collections

### SolarSystem

Views of the solar system. Uses `astroquery` to retrieve orbit data from the JPL Horizons system for major bodies and the Minor Planet Center orbit
database (MPCORB) for asteroids, TNOs, Centaurs, and comets.  Code in the notebooks solves Kepler's equations numerically to compute positions and
full orbits in XYZ ecliptic coordinates to make plots of the appearance of the solar system.

### ProperMotions

Proper motion and parallax animations using `astroquery` to retrieve astrometric data from the Gaia DR3 database. The parallax GIF animations are
based on Eric Tollerud's demo notebooks of Gaia DR3 queries, modified to show particular features relevant for 2nd-year astrophysics but also nice
to show gen-ed ("Astro101") courses.

Also has a notebook that uses Gaia and Hipparcos data to plot motions of the stars in the direction of the Big Dipper asterism, and create still frames
ready to be combined into an animation of that motion using tools like `ffmpeg`.

## Dependencies

Written and tested with Python 3.12 (Anaconda distro), using the following packages.
 * `matplotlib` version 3.9.2
 * `numpy` version 1.26.4
 * `astropy` version 7.0
 * `astroquery` version 0.4.9
 * `scipy` version 1.13.1 (various numerical solvers)
 * `pandas` version 2.2.2
 * ...

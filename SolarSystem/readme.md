# Solar System Views

Plot Solar System orbits and groups of objects (time snapshots).

We try to make these self-contained by using `astroquery` to retrieve data from the Minor Planet Center orbit database (MPCORB) and
the JPL Horizons database.  To keep things simple, we adopt a single-epoch osculating element for a planet or body orbit, and the
notebooks use a Newton-Raphson root finder to solve Kepler's equations to draw the orbits.

## General Views

 * `Solar System Views.ipynb` - views looking down on the solar system at various scales for the major planets
 * `Solar System Dwarfs.ipynb` - orbits of the dwarf planets (including candidates with known mass)
 * `Solar System Asteroids.ipynb` - Main asteroid belt, Trojans, Hildas, Hungarias, and Phocaeas with planet orbits out to Jupiter
 * `Solar System TNOs.ipynb` - Trans-Neptunian Objects and Centaurs with outer solar system major planets
 * `Solar System Comets.ipynb` - Solar system and selected short and long-period comets (most of those visited by spacecraft)

## Specialty Views

More technical views for advanced classes.

 * `Kirkwood Gaps.ipynb` - histogram showing the Kirkwood gaps in the asteroid belt with Jupiter mean-motion resonance lines plotted.
 * `Jupiter_Tisserand.ipynb` - Jupiter Tisserand parameter for asteroids and Jupiter-family comets
 * `Neptune_Tisserand.ipynb` - Neptune Tisserand parameter for TNOs and short-period comets
 * `TNOs_aePlot.ipynb` - Plot of eccentricty vs. semimajor axis for TNOs plotting lines of constant perihelion showing resonances and scattered objects
 * `Stern-Levison_Lambda.ipynb` - Plot of the Stern-Levison Lambda parameter for distinguishing major and dwarf planets.

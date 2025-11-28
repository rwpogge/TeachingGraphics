# Human Eye Quantum Efficiency

The human eye uses rod and cone cells in the retina to sense light.  Cone cells are responsible for color vision
and most sensitive at bright light levels, whereas the rod cells are more sensitive at low light levels and
monochromatic in their response.

There are thus two luminous efficiency curves for the human eye:
 * Photopic Sensitivity: normal light levels, nominal peak QE 0.5%
 * Scotopic Sensitivity: low light levels, nominal peak QE 5%
 
The normalized luminous efficiencies we plot are
 * Photopic: [Sharpe, Stockman, Jagla, & Jaegle (2005)](https://jov.arvojournals.org/article.aspx?articleid=2121738)
 * Scotopic: CIE 1951

A fun technical read about how this is measured is van Meeteren, 1997, Vision Res, 18, 257 [https://www.sciencedirect.com/science/article/abs/pii/0042698978901608?via%3Dihub] (yes, I, too, think papers older than 20 years should be in the public domain. Thanks, Elsevier).

This notebook plots the photopic and scotopic quantum efficiency of the
human eye in linear and logarithmic form.

# Atmospheric Infrared Transmission


## Data Source:

  www.gemini.edu/sciops/telescopes-and-sites/observing-condition-constraints

At near-IR (0.9-6um), they provide calculations for airmasses 1.0, 1.5, and 
2.0 for water vapor columns of 1.0, 1.6, and 3.0mm of precipitable water, 
respectively (9 data tables).  Data are calculated by ATRAN (Lord 1992).

For Mid-IR (6-28um), the data are provided for airmass 1.5 for water columns
of 1.0, 1.6, 3.0, and 5.0mm of precipitable water.  Also from ATRAN (Lord 1992)

## Citation

Lord, S.D. 1992, NASA Technical Memorandum 103957 (https://ui.adsabs.harvard.edu/abs/1992nstc.rept.....L)

The ADS link has the BibTeX entry if you are citing the work using LaTeX.

Please also site the sources as cite the Gemini Observatory, and this GitHub repository for the plot 
or code.

### 0.9-5.6um near-IR atmospheric transmission

```
 1.0mm H20, airmass=1.0
```

### 6-28um mid-IR atmospheric transmission

```
  mid-IR sky transmission 6 - 28 um
 1.0mm H2O, sec z = 1.5

 Modification of original spectrum from ATRANS via Tom Geballe
 14Dec99 - converted to units of nm from um Phil Puxley
```
There is a small gap in wavelength between the near- and mid-IR spectra between 5.6 and 6um.  This is
deep in the saturated core of the water-vapor absorption feature and so basically all 0s. I just leave
the gap as it is in the data.  

The mid-IR spectrum is for a zenith distance of 48-degrees instead of at the zenith like the near-IR
spectrum, but the difference isn't important for the illustration of the deep molecular absorption bands.

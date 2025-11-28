# Stellar spectral types and colors

A series of plots illustrating stellar spectral types, luminosity types,
and colors

## MKK Spectral Types

Plot of optical spectra of representative stellar dwarf spectral types.

All of these are dwarf stars, types O5 thru M5, from A Library of
Stellar Spectra by Jacoby, Hunter, & Christian 1984, ApJ, 56,
257. Data have been rescaled to have unity flux at 5500A and then were
shifted by an arbitrary consant so that they will appear in a vertical
stack without overlaps.

## Dwarf T<sub>eff</sub> and (B-V) Color

Uses Eric Mamajek's "A Modern Mean Dwarf Stellar Color and Effective Temperature Sequence"
 * http://www.pas.rochester.edu/~emamajek/EEM_dwarf_UBVIJHK_colors_Teff.txt

Version 2022.04.16

Slight modification of the input file to make everything not the data header or data table a comment 
including the extensive notes at the end of the file.

Plots T<sub>eff</sub> vs (B-V) color for dwarf stars.

## Vega spectrum and UBVRI filter bandpasses

Plot of the spectrum of Vega and the standard UBVRI filter bandpasses,
showing the part of the spectrum covered by each filter.  Vega is the
zero point of the stellar magnitude system.

## Main Sequence Mass-Luminosity Relation

Main-sequence mass-luminosity relation using data from [Eker et al. 2018, MNRAS, 479, 5491](https://ui.adsabs.harvard.edu/abs/2018MNRAS.479.5491E).

Selection criteria: Exclude stars
 * tagged by Eker et al. as types 1,2,3 (discarded for various reasons)
 * tagged as GLB (globlar cluster stars)
 * with luminosity classes III, IV, or IV-V
 * with mass and radius errors >10%
 * with luminosity errors >40%

The data were further augmented by computing logL from logR and logT from the original Eker et al. 
table (provided to use by Eker as a CSV file).

## Main Sequence Mass-Radius Relation

Plot of stellar radius R as a function of Mass M for the same set of main sequence stars used in the
associated Mass-Luminosity figures.

Data from [Eker et al. 2018, MNRAS, 479, 5491](https://ui.adsabs.harvard.edu/abs/2018MNRAS.479.5491E).

Selection criteria: Exclude stars
 * tagged by Eker et al. as types 1,2,3 (discarded for various reasons)
 * tagged as GLB (globlar cluster stars)
 * with luminosity classes III, IV, or IV-V
 * with mass and radius errors >10%
 * with luminosity errors >40%

The data were further augmented by computing logL from logR and logT from the original Eker et al. 
table (provided to use by Eker as a CSV file).




# Reference data used on the site (public, openly licensed)

## polystyrene_atr_FTIR-Plastics-C4_PS120.csv
- What: one ATR-FTIR spectrum of polystyrene (consumer PS: medicine/toy/disposable-dish items), %T vs wavenumber, 4000–400 cm⁻¹, 4 cm⁻¹ resolution, 32 scans, Jasco FT/IR with ATR PRO 4X accessory.
- Source: Villegas Camacho O., Alejo Eleuterio R., Francisco Valencia I., Granda Gutiérrez E., Martínez Gallegos S., Illescas J. (2024). *FTIR-Plastics: a Fourier Transform Infrared Spectroscopy dataset for the six most prevalent industrial plastic polymers* [Data set]. Zenodo. https://doi.org/10.5281/zenodo.10736650 — file `FTIR-PLASTIC.zip › FTIR-PLASTIC-c4/PS_c4.zip › PS120.csv` (record v1, 1 March 2024).
- Licence: Creative Commons Attribution 4.0 International (CC BY 4.0), as stated on the Zenodo record (`license: cc-by-4.0`, checked 19 Oct 2026).
- Why this file: of the 500 PS spectra, PS120 scored highest on clean polystyrene bands (3060/3025, 2921/2848, 1601, 1492/1451, 1028, 749, 694 cm⁻¹) with low baseline noise and no polypropylene 1375 cm⁻¹ band (some files in the PS set are other polymers).
- Changes made: file copied unchanged. For display, the home-page hero (`FtirHero.astro`) uses a min–max downsample (pairs of extreme points per 8-point bucket, values rounded to 0.1) and plots 2000–400 cm⁻¹ at twice the scale of 4000–2000 cm⁻¹, as classic IR chart paper does. %T values are not normalised (the ATR baseline sits near 104 %T in the original).
- Caption used on the site: "Reference spectrum: polystyrene (ATR-FTIR), FTIR-Plastics dataset, Villegas Camacho et al. 2024, Zenodo, CC BY 4.0 — illustrative, not an MCL result."
- Not used: NIST Chemistry WebBook spectra (NIST SRD 69 data are not openly licensed); Open Specy library (OSF licence field "Other").

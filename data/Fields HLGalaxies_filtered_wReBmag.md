## Fields in HLGalaxies_filtered_wReBmag.csv
### File source
The `HLGalaxies_filtered_wReBmag.csv` file is created at the end of the `HLgalaxies_SDSS_extract.ipynb` Jupyter notebook. It includes data extracted from the **Hyperleda database** created in the previous Jupyter notebook (`Hyperleda_load.ipynb`) and uses this as a foundation/starting point upon which to build data. Additional calculated fields are included to determine (and compare) the effective radius of the galaxies calculated through a number of methods.

### Field description
The columns in the HLGalaxies_filtered_wReBmag.csv file include all those in the HLGalaxies_filtered.csv with augmented SDSS data. The total fields with descriptions are as follows:

| Field              | Units           | Description                                                                                                                                                  | Source |
|--------------------|-----------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|--------|
| Name               |                 | Principal name (pgc)                                                                                                                                         | HL     |
| RA                 | degrees decimal | RA 2000                                                                                                                                                      | HL     |
| DEC                | degrees decimal | DEC 2000                                                                                                                                                     | HL     |
| l                  | degrees decimal | Galactic Longitude                                                                                                                                           | HL     |
| b                  | degrees decimal | Galactic Latitude                                                                                                                                            | HL     |
| extinct            | mag             | Galactic extinction in B-Band (ag)                                                                                                                           | HL     |
| eff_B-V            | mag             | Effective B-V color                                                                                                                                          | HL     |
| t                  |                 | Morphological type code                                                                                                                                      | HL     |
| type               |                 | Morphological type                                                                                                                                           | HL     |
| v                  | km/s            | Mean Heliocentric radial velocity (cz)                                                                                                                       | HL     |
| e_v                | km/s            | Actual error on v                                                                                                                                            | HL     |
| dist_Hf            | pc              | Distance estimate (v/70)                                                                                                                                     | calc   |
| bt                 | mag             | Total B magnitude                                                                                                                                            | HL     |
| e_bt               | mag             | Actual error on bt                                                                                                                                           | HL     |
| Bmagt              | mag             | Absolute B magnitude [-(modbest-bt)]                                                                                                                         | calc   |
| it                 | mag             | Total I-magnitude                                                                                                                                            | HL     |
| e_it               | mag             | Actual error on it                                                                                                                                           | HL     |
| ut                 | mag             | Total U-magnitude                                                                                                                                            | HL     |
| vt                 | mag             | Total V-magnitude                                                                                                                                            | HL     |
| modbest            | mag             | Best distance modulus, combining mod0 and modz                                                                                                               | HL     |
| e_modbest          | mag             | Actual error on modbest                                                                                                                                      | HL     |
| dist_Mpc           | Mpc             | Distance estimate from 10*(10^(modbest/5))/1E6                                                                                                               | calc   |
| logd25             | log(0.1 arcmin) | log of apparent diameter (d25 in 0.1 arcmin)                                                                                                                 | HL     |
| hl_names(pgc)      |                 | Comma separated list of all designations for object "pgc"                                                                                                    | HL     |
| appDiam_arcsec     | arcsec          | Diameter in arcsec based on logD25                                                                                                                           | calc   |
| appDiam_kpc        | kpc             | Diameter in kpc based on logD25                                                                                                                              | calc   |
| est_vt             | mag             | Est. of vt from existing bt                                                                                                                                  | calc   |
| est_Vmagt          | mag             | Est. of Abs V mag from vt and modbest                                                                                                                        | calc   |
| Sn                 |                 | Specific frequency                                                                                                                                           | calc   |
| Ngc                |                 | Estimated number of GCs                                                                                                                                      | calc   |
| sigma_G            |                 | Gaussian SD G-band                                                                                                                                           | calc   |
| mu_g               |                 | Gaussian mean - g-band                                                                                                                                       | calc   |
| vis_GCs            |                 | Est. number of visible GCs                                                                                                                                   | calc   |
| pc_vis_GCs         | %               | Est. number of visible GCs as % of total hosted                                                                                                              | calc   |
| SDSSobjID          |                 | Unique SDSS identifier composed from [skyVersion, rerun,run,camcol,field,obj]                                                                                | SDSS   |
| SDSSnChild         |                 | Number of children if this is a composite object  that has been deblended. BRIGHT (in a flags sense)  objects also have nchild == 1, the non-BRIGHT sibling. | SDSS   |
| SDSSra             | degrees decimal | J2000 Right Ascension (r-band)                                                                                                                               | SDSS   |
| SDSSdec            | degrees decimal | J2000 Declination (r-band)                                                                                                                                   | SDSS   |
| SDSSdistance       | arcmin          | Distance to nearest SDSS object (3 arcsec cone)                                                                                                              | SDSS   |
| petroMag_g         | mag             | Petrosian magnitude (g-band)                                                                                                                                 | SDSS   |
| petroR50_g         | arcsec          | Radius containing 50% of Petrosian flux (g-band)                                                                                                             | SDSS   |
| petroR90_g         | arcsec          | Radius containing 90% of Petrosian flux (g-band)                                                                                                             | SDSS   |
| deVRad_g           | arcsec          | de Vaucouleurs fit scale radius, here defined  to be the same as the half-light radius, also  called the effective radius. (g-band)                          | SDSS   |
| expRad_g           | arcsec          | Exponential fit scale radius, here defined to  be the same as the half-light radius, also  called the effective radius. (g-band)                             | SDSS   |
| petroMag_r         | mag             | Petrosian magnitude (r-band)                                                                                                                                 | SDSS   |
| petroR50_r         | arcsec          | Radius containing 50% of Petrosian flux (r-band)                                                                                                             | SDSS   |
| petroR90_r         | arcsec          | Radius containing 90% of Petrosian flux (r-band)                                                                                                             | SDSS   |
| deVRad_r           | arcsec          | de Vaucouleurs fit scale radius, here defined  to be the same as the half-light radius, also  called the effective radius. (r-band)                          | SDSS   |
| expRad_r           | arcsec          | Exponential fit scale radius, here defined to  be the same as the half-light radius, also  called the effective radius. (r-band)                             | SDSS   |
| Re_SDSS_g_calc     | arcsec          | Effective radius from SDSS g-band data                                                                                                                       | calc   |
| Re_SDSS_r_calc     | arcsec          | Effective radius from SDSS r-band data                                                                                                                       | calc   |
| Re_SDSS_g_calc_kpc | kpc             | Effective radius from SDSS g-band data                                                                                                                       | calc   |
| Re_SDSS_r_calc_kpc | kpc             | Effective radius from SDSS r-band data                                                                                                                       | calc   |
| Re_BmagCalc_kpc    | kpc             | Effective radius calibrated to B mag                                                                                                                         | calc   |
| Re_BmagCalc_arcsec | arcsec          | Effective radius calibrated to B mag                                                                                                                         | calc   |

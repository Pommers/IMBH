## Fields in datafile HLGalaxies_filtered.csv
### File source


### Field description
The columns in the HLGalaxies_filtered.csv file include all those in the HLG2.csv with additional calculated data. The summary fields with descriptions are as follows:

| Field              | Units           | Description                                               | Source |
|--------------------|-----------------|-----------------------------------------------------------|--------|
| Name               |                 | Principal name (pgc)                                      | HL     |
| RA                 | degrees decimal | RA 2000                                                   | HL     |
| DEC                | degrees decimal | DEC 2000                                                  | HL     |
| l                  | degrees decimal | Galactic Longitude                                        | HL     |
| b                  | degrees decimal | Galactic Latitude                                         | HL     |
| extinct            | mag             | Galactic extinction in B-Band (ag)                        | HL     |
| eff_B-V            | mag             | Effective B-V color                                       | HL     |
| t                  |                 | Morphological type code                                   | HL     |
| type               |                 | Morphological type                                        | HL     |
| v                  | km/s            | Mean Heliocentric radial velocity (cz)                    | HL     |
| e_v                | km/s            | Actual error on v                                         | HL     |
| dist_Hf            | pc              | Distance estimate (v/70)                                  | calc   |
| bt                 | mag             | Total B magnitude                                         | HL     |
| e_bt               | mag             | Actual error on bt                                        | HL     |
| Bmagt              | mag             | Absolute B magnitude [-(modbest-bt)]                      | calc   |
| it                 | mag             | Total I-magnitude                                         | HL     |
| e_it               | mag             | Actual error on it                                        | HL     |
| ut                 | mag             | Total U-magnitude                                         | HL     |
| vt                 | mag             | Total V-magnitude                                         | HL     |
| modbest            | mag             | Best distance modulus, combining mod0 and modz            | HL     |
| e_modbest          | mag             | Actual error on modbest                                   | HL     |
| dist_Mpc           | Mpc             | Distance estimate from 10*(10^(modbest/5))/1E6            | calc   |
| logd25             | log(0.1 arcmin) | log of apparent diameter (d25 in 0.1 arcmin)              | HL     |
| hl_names(pgc)      |                 | Comma separated list of all designations for object "pgc" | HL     |
| appDiam_arcsec     | arcsec          | Diameter in arcsec based on logD25                        | calc   |
| appDiam_kpc        | kpc             | Diameter in kpc based on logD25                           | calc   |
| est_vt             |                 | Est. of vt from existing bt                               | calc   |
| est_Vmagt          |                 | Est. of Abs V mag from vt and modbest                     | calc   |
| Sn                 |                 | Specific frequency                                        | calc   |
| Ngc                |                 | Estimated number of GCs                                   | calc   |
| sigma_G            |                 | Gaussian SD G-band                                        | calc   |
| mu_g               |                 | Gaussian mean - g-band                                    | calc   |
| vis_GCs            |                 | Est. number of visible GCs                                | calc   |
| pc_vis_GCs         |                 | Est. number of visible GCs as % of total hosted           | calc   |


## Fields in datafile galalertobj_detail.csv
### File source
The `galalertobj_detail.csv` file is a summary file created from the detail of each of the ZTF objects (and most recent candidate alert associated with it), additional data includes cross-correlation of the alert with other catalogues and databases, including the Transient Name Server (TNS), SIMBAD, and GAIA.

### Field description
A list of the columns are included below:

| Name             | Units   | Description                                                                | Source |
|------------------|---------|----------------------------------------------------------------------------|--------|
| name             |         | Unique identifier (from ZTF Object name and Candidate ID)                  | code   |
| objid            |         | Alert Object identifier                                                    | ZTF    |
| candid           |         | Alert Candidate identifier                                                 | ZTF    |
| ra               | degrees | Alert J2000 RA                                                             | ZTF    |
| dec              | degrees | Alert J2000 DEC                                                            | ZTF    |
| distnr           | pixels  | Distance to nearest source in reference image PSF-catalog within 30 arcsec | ZTF    |
| gals             |         | Host galaxy name                                                           | code   |
| consolid         |         | Consolidated ID (from below)                                               | code   |
| tnsid            |         | Transient Name Server (TNS) Identifier                                     | TNS    |
| tnstype          |         | TNS designated type                                                        | TNS    |
| tnsdiscoverydate |         | TNS discovery date                                                         | TNS    |
| tnsdiscoverymag  | mag     | TNS discovery magnitude                                                    | TNS    |
| simbadid         |         | SIMBAD identifier                                                          | SIMBAD |
| gaiadesignation  |         | GAIA archive identifier                                                    | GAIA   |
| gaiaprllx        |         | GAIA parallax (if present)                                                 | GAIA   |
| gaiadist         |         | GAIA parallax distance                                                     | GAIA   |

# Awesome Astronomy [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

An [awesome list](https://github.com/sindresorhus/awesome) of resources for professional astronomers.  *Everyone* is invited to [contribute](CONTRIBUTING.md) by pull request.

## Contents

- [Blogs](#blogs)
- [Codes](#codes)
- [Conferences](#conferences)
- [Datasets](#datsets)
- [Social Media](#social-media)

***

### Blogs

- [AAS Policy Blog](http://aas.org/policy/policy-blog) Josh Shiode
- [AstroBetter](http://www.astrobetter.com/) Kelle Cruz and many other contributors
- [Astrobiased](http://www.astrobiased.com/) Eli Bressert
- [astrobites](https://astrobites.org/) The astro-ph reader's digest
- [AstroWright](http://sites.psu.edu/astrowright/) Jason Wright
- [dan foreman-mackey](http://dan.iel.fm/posts/) Daniel Foreman-Mackey
- [Hogg Blog](http://hoggresearch.blogspot.com/) David W. Hogg
- [gully](http://gully.github.io/blog/) Michael Gully-Santiago
- [Pythonic Perambulations](https://jakevdp.github.io/) Jacob T. VanderPlas
- [SarahAskew](http://sarahaskew.net/) Sarah Kendrew

### Codes
*All codes are in `Python` unless otherwise noted*

#### General purpose

- [Astronomy Source Code Library](http://ascl.net/) - A free online registry for source codes of interest to astronomers and astrophysicists.
- [Continuum Anaconda](https://www.continuum.io/why-anaconda) - Install, update, manage Python environments.
- [ztv](https://github.com/henryroe/ztv) - An astronomical image viewer written in Python.
- [AplPy](http://aplpy.github.io) - a Python module for astronomical imaging data.
- [Astropy](http://astropy.org) - Core package for Astronomy in Python.
- [AstroML](http://www.astroml.org) - Companion textbook *Statistics, Data Mining, and Machine Learning in Astronomy*.
- [Emcee](http://dan.iel.fm/emcee/current/) - Seriously kick-ass MCMC.
- [ExoData](https://github.com/ryanvarley/ExoData) - [Open Exoplanet Catalogue](https://github.com/OpenExoplanetCatalogue) interface and exploratory analysis tool.
- [gala](https://github.com/adrn/gala) - Galactic and gravitational dynamics in Python
- [GalPy](https://github.com/jobovy/galpy) - Galactic Dynamics in python.
- `IDL` [NASA'S IDL Astronomy User's Library](http://idlastro.gsfc.nasa.gov/) - large libary with plenty of very useful code for astronomers
- [The LSST Stack](https://confluence.lsstcorp.org/display/LSWUG/Using+the+LSST+Stack) Conda-installable codes for working with LSST simulation data and some existing data.
Detrending & Analysis

#### Spectroscopy

 - [Starfish](https://github.com/iancze/Starfish) - Tools for Flexible Spectroscopic Inference

#### PSF photometry and source detection

 - `R` [ProFound](https://github.com/asgr/ProFound) - Source finding and extraction
 - [PSFutils](https://github.com/spacetelescope/psfutils) - Open-source Python package to provide convenience tools for working with point-spread functions.

#### Visualization

- [astro_animations](https://github.com/zingale/astro_animations) - Various animations used for teaching introductory astronomy concepts

#### Kepler/K2/TESS

*Detrending*

- [PyKE](http://github.com/KeplerGO/PyKE) - Kepler, K2 & TESS Data Analysis Tools
- [everest](http://github.com/rodluger/everest) - De-trending of K2 Light curves
- [k2sc](http://github.com/OxES/k2sc) - K2 systematics correction using Gaussian processes
- [nutella](http://github.com/benmontet/nutella) - Great (point) spreads for beautiful Kepler/K2 inference
- [skope](http://github.com/nksaunders/skope) - Synthetic K2 Objects for PLD Experimentation
- [k2phot](http://github.com/petigura/k2phot) - public k2phot code from Erik Petigura
- [K2-CPM](http://github.com/jvc2688/K2-CPM) - K2 Causal Pixel Model
- [halophot](https://github.com/hvidy/halophot/) - K2 Halo Photometry for very bright stars
- [cave](http://github.com/nksaunders/cave) - Crowded Aperture Variability Extraction
- [celerite-asteroseis](http://github.com/skgrunblatt/celerite-asteroseis) - Transit fitting and basic time-domain asteroseismology using celerite and ktransit
- [k2photometry](http://github.com/vincentvaneylen/k2photometry) - Read, reduce and detrend K2 photometry and search for transiting planets
- [keplersmear](http://github.com/benjaminpope/keplersmear) - Make light curves from Kepler and K2 collateral data
- [OxKeplerSC](http://github.com/OxES/OxKeplerSC) - Kepler jump and systematics correction using Variational Bayes and shrinkage priors.
- [K2Pipeline](http://github.com/FGCUStellarResearch/K2Pipeline) - Data reduction and detrending pipeline for K2 data in Matlab
- [PySysRem](http://github.com/stephtdouglas/PySysRem) - A Python implementation of the SysRem algorithm from Tamuz, Mazeh, and Zucker (2004)

*Full Frame Images*

- [f3](http://github.com/benmontet/f3) - Full Frame Fotometry from the Kepler Full Frame Images
- [FFIorBUST](http://github.com/jradavenport/FFIorBUST) - Make really bad light curves from the Kepler Full Frame Images
- [kepcal](http://github.com/dfm/kepcal) - Self calibration using the Kepler FFIs

*Data Access*

- [kplr](http://github.com/dfm/kplr) - Tools for working with Kepler data using Python
- [kepFGS](http://github.com/christinahedges/kepFGS) - Tools to use the Kepler and K2 Fine Guidance Sensor data.
- [k2plr](http://github.com/rodluger/k2plr) - Fork of dfm/kplr with added k2 functionality


*Metadata*

- [kadenza](http://github.com/KeplerGO/kadenza) - Converts raw cadence target data from the Kepler space telescope into FITS files.
- [k2-quality-control](http://github.com/KeplerGO/k2-quality-control) - Automated quality control of Kepler/K2 data products.
- [SuperstampFITS](http://github.com/amcody/SuperstampFITS) - Create individual FITS files of K2 superstamp regions.
- [keputils](http://github.com/timothydmorton/keputils) - Basic module for interaction with KOI and Kepler-stellar tables.

*Planet Search*


- [PyTransit](http://github.com/hpparvi/PyTransit) - Fast and easy transit light curve modeling using Python and Fortran.
- [batman](http://github.com/lkreidberg/batman) - Fast transit light curves models in Python.
- [ktransit](http://github.com/mrtommyb/ktransit) - A simple exoplanet transit modeling tool in python
- [planetplanet](http://github.com/rodluger/planetplanet) - A general photodynamical code for exoplanet light curves
- [ketu](http://github.com/dfm/ketu) - I can haz planetz?
- [ttvfast-python](http://github.com/mindriot101/ttvfast-python) - Python interface to the TTVFast library
- [terra](http://github.com/petigura/terra) - Transit Detection Code
- [pysyzygy](http://github.com/rodluger/pysyzygy) - A fast and general planet transit (syzygy) code written in C and in Python
- [k2ps](http://github.com/hpparvi/k2ps) - K2 Planet Search
- [lcps](http://github.com/matiscke/lcps) - A tool for pre-selecting light curves with possible transit signatures
- [exocartographer](https://github.com/bfarr/exocartographer) - A forward-modeling tool for constraining surface maps orbital parameters of exoplanets from time-resolved photometry


*Population Statistics*


- [VESPA](http://github.com/timothydmorton/VESPA) - Calculating false positive probabilities for transit signals
- [kepler-robovetter](http://github.com/nasa/kepler-robovetter) - The Kepler Prime Robovetter
- [koi-fpp](http://github.com/timothydmorton/koi-fpp) - False positive probabilities for all KOIs
- [KeplerPORTS](http://github.com/nasa/KeplerPORTS) - The Kepler Pipeline
- [Kepler-FLTI](http://github.com/nasa/Kepler-FLTI) - Kepler Prime Flux-Level Transit Injection


*Positional*


- [K2fov](http://github.com/KeplerGO/K2fov) - Check whether targets are in the field of view of NASA's K2 space telescope
- [K2ephem](http://github.com/KeplerGO/K2ephem) - Check whether a Solar System body is (or was) observable by NASA's K2 mission.
- [k2-pix](http://github.com/stephtdouglas/k2-pix) - Overlay a sky survey image on a K2 target pixel stamp
- [k2flix](http://github.com/barentsen/k2flix) - Create quicklook movies from the pixel data observed by Kepler/K2/TESS
- [k2mosaic](http://github.com/barentsen/k2mosaic) - Mosaic Target Pixel Files (TPFs) obtained by NASA's Kepler/K2 missions into images and movies.
- [tvguide](http://github.com/tessgi/tvguide) - A tool for determining whether stars and galaxies are observable by TESS.


*Science / Astrophysics*


- [isochrones](http://github.com/timothydmorton/isochrones) - Pythonic stellar model grid access; easy MCMC fitting of stellar properties
- [ldtk](http://github.com/hpparvi/ldtk) - Python toolkit for calculating stellar limb darkening profiles
- [isoclassify](http://github.com/danxhuber/isoclassify) - Perform stellar classifications using isochrone grids
- [appaloosa](http://github.com/jradavenport/appaloosa) - Python-based flare finding code for Kepler light curves.
- [pymacula](http://github.com/timothydmorton/pymacula) - Python wrapper for Macula analytic starspot code
- [MulensModel](http://github.com/rpoleski/MulensModel) - Microlensing Modelling package
- [animate_spots](http://github.com/stephtdouglas/animate_spots) - Make frames for animated gifs/movies showing a rotating spotted star
- [spotrod](https://github.com/bencebeky/spotrod) - A semi-analytic model for transits of spotted stars -- C implementation and Python API
- [decatur](http://github.com/jadilia/decatur) - Tidal Synchronization of Kepler Eclipsing Binaries


*Other*

- [PandExo](http://github.com/natashabatalha/PandExo) - A Community Tool for Transiting Exoplanet Science with the JWST & HST
- [kepler_orrery](http://github.com/ethankruse/kepler_orrery) - Make a Kepler orrery gif or movie of all the Kepler multi-planet systems
- [radvel](http://github.com/California-Planet-Search/radvel) - General Toolkit for Modeling Radial Velocity Data
- [koi3278](http://github.com/ethankruse/koi3278) - Analysis files for the KOI-3278 system
- [trappist1](http://github.com/rodluger/trappist1) - TRAPPIST-1 photometry with K2

#### Instrumentation

- [binaryoffset](https://github.com/snfactory/binaryoffset) - Detecting and Correcting the Binary Offset Effect in CCDs


### Conferences

- [International Astronomy Meetings](http://www.cadc-ccda.hia-iha.nrc-cnrc.gc.ca/en/meetings/) - List of all planned Astronomy Conferences
- [Python in Astronomy](http://openastronomy.org/pyastro/) - A conference series focusing on the use, development, and community surrounding Python packages for all types of Astronomy.

### Datasets

- [AAVSO APASS](http://www.aavso.org/apass) Optical all sky data.
- [AAVSO Data](https://www.aavso.org/data-download) - Long time baseline data for variable stars.
- [AllWISE](http://irsa.ipac.caltech.edu/Missions/wise.html) - Wide Field Infrared Survey Explorer.
- [AstroML](http://www.astroml.org/user_guide/datasets.html) - Tools and data sets, including SDSS, LINEAR light curves, LIGO data.
- [GALEX SQL query](http://galex.stsci.edu/casjobs/) - Galex data.
- [Hipparcos](http://heasarc.gsfc.nasa.gov/W3Browse/all/hipparcos.html) - Subset of HYG.
- [HYG](http://www.astronexus.com/hyg)- Database containing all stars in Hipparcos, Yale Bright Star, and Gliese catalogs (almost 120,000 stars, 14 MB).
- [LINEAR](http://www.astro.washington.edu/users/ivezic/linear/PaperIII/PLV.html) - 7194 LINEAR variables with light curve classification.
- [MAST](https://archive.stsci.edu/) - The Mikulski Archive for Space Telescopes houses astronomical data sets in the optical, ultraviolet, and near-infrared parts of the spectrum
- [NOAO Data Lab](https://datalab.noao.edu/) -  Offers large datasets now being generated by instruments on NOAO and other wide-field telescopes.
- [OGLE](http://ogledb.astrouw.edu.pl/~ogle/CVS/) - Variable stars towards OGLE-III fields in the Magellanic Clouds and Galactic bulge
- [Open Exoplanet Catalogue](https://github.com/OpenExoplanetCatalogue) - An open source database of all discovered extrasolar planets.
- [Research-based Science Education for Undergraduates](http://rbseu.uaa.alaska.edu/index.html) - Curated datasets on 7 projects designed for undergraduates.
- [SDSS SQL query](http://skyserver.sdss.org/dr12/en/proj/advanced/hr/sql.aspx) - Sloan Digital Sky Survey.
- [SDSS for Teachers](http://cas.sdss.org/dr5/en/proj/teachers/) - Includes basic projects and advanced projects
- [Supernova Cosmology Project](http://supernova.lbl.gov/union/) The Union2.1 SN Ia compilation of 883 SNe from 19 datasets.

### Future Datasets

- [ARCHES](http://www.arches-fp7.eu/index.php/tools-data/accessing-data) - XMM-Newton cross match database
- [Pan-Starrs](http://ipp.ifa.hawaii.edu/index.php) - Public data release coming soon.

### Social Media

- [Astronomer's Facebook Group](https://www.facebook.com/groups/123898011017097/) - Closed group for professional astromers, with over 8000 members.
- [Astronomers on Twitter](http://truesciphi.org/ast.html) - List of Astronomers on Twitter with over 1000 followers.
- [Astromers.io](http://astronomers.io/) - "A nice place for astronomers, and those working in the sphere of professional astronomy"
- [Community.lsst.org](https://community.lsst.org) - A community forum for using/developing LSST software and doing science with LSST.
- [Python Users in Astronomy](https://www.facebook.com/groups/astropython/) - A closed group for python users in astronomy.

****

Licensed [Creative Commons Zero](LICENSE).

[This exists because they told me to do it.](https://twitter.com/exoplaneteer/status/600452917779308544)

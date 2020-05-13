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

- [Andy Casey's ads](https://github.com/andycasey/ads) - Python tool for ADS
- [Astronomy Source Code Library](http://ascl.net/) - A free online registry for source codes of interest to astronomers and astrophysicists.
- [Continuum Anaconda](https://www.continuum.io/why-anaconda) - Install, update, manage Python environments.
- [AplPy](http://aplpy.github.io) - a Python module for astronomical imaging data.
- [Astropy](http://astropy.org) - Core package for Astronomy in Python.
- [Astropy tutorials](https://github.com/astropy/astropy-tutorials) - Tutorials for the Astropy Project
- [AstroML](http://www.astroml.org) - Companion textbook *Statistics, Data Mining, and Machine Learning in Astronomy*.
- [celerite](https://github.com/dfm/celerite) - Scalable 1D Gaussian Processes in C++, Python, and Julia
- [Emcee](http://dan.iel.fm/emcee/current/) - Seriously kick-ass MCMC.
- [ExoData](https://github.com/ryanvarley/ExoData) - [Open Exoplanet Catalogue](https://github.com/OpenExoplanetCatalogue) interface and exploratory analysis tool.
- [fast-histogram](https://github.com/astrofrog/fast-histogram) - Fast 1D and 2D histogram functions in Python
- `IDL` [NASA'S IDL Astronomy User's Library](http://idlastro.gsfc.nasa.gov/) - large libary with plenty of very useful code for astronomers
- [The LSST Stack](https://confluence.lsstcorp.org/display/LSWUG/Using+the+LSST+Stack) Conda-installable codes for working with LSST simulation data and some existing data.
Detrending & Analysis
- [sncosmo](https://github.com/sncosmo/sncosmo) - Python library for supernova cosmology
- [Pandas Profiling](https://github.com/pandas-profiling/pandas-profiling) - Create HTML profiling reports from pandas DataFrame objects.
- [Python Data Science Handbook](https://github.com/jakevdp/PythonDataScienceHandbook) - Python Data Science Handbook: full text in Jupyter Notebooks


#### Astrometry / Kinematic / RV / Galactic / Gaia

- [Banyan Sigma](https://github.com/jgagneastro/banyan_sigma) - A Bayesian classifier to identify members of the 27 nearest young associations within 150 pc of the Sun
- [Barycorrpy](https://github.com/shbhuk/barycorrpy) - Calculate the barycentric velocity correction for a star with an accuracy well below 1 cm/s.
- [gaia on tap](https://github.com/andycasey/gaia-on-tap) - Python utilities and examples for accessing Gaia data using the Table Access Protocol (TAP)
- [gaia tools](https://github.com/jobovy/gaia_tools) - Tools for working with the ESAGaia data and related data sets
- [gala](https://github.com/adrn/gala) - Galactic and gravitational dynamics in Python
- [GalPy](https://github.com/jobovy/galpy) - Galactic Dynamics in python.
- [Luminosity Calibration Tutorial](https://github.com/agabrown/luminosity-calibration-tutorial) - Tutorial on use of parallaxes in luminosity calibration; accompanies a Gaia DR2 paper on the proper use of parallaxes (Luri et al. in prep)
- [vaex](https://github.com/maartenbreddels/vaex) - Lazy Out-of-Core DataFrames for Python, visualize and explore big tabular data at a billion rows per second.
- [ExoSOFT](https://github.com/kylemede/ExoSOFT) - Solves for the orbital elements of any single companion, provided observed radial velocity and/or astrometry.
- [pyaneti](https://github.com/oscaribv/pyaneti) - A multi-planet Radial Velocity and Transit fit software
- [PyGaia](https://github.com/agabrown/PyGaia) - Python toolkit for basic Gaia data simulation, manipulation, and analysis
- [radvel](http://github.com/California-Planet-Search/radvel) - General Toolkit for Modeling Radial Velocity Data


#### Spectroscopy

 - [Apogee](https://github.com/jobovy/apogee) - Tools for dealing with APOGEE data
 - [Chimera](https://github.com/ExoCTK/chimera) - Atmospheric retrieval code from Mike Line
 - [The](https://github.com/mkness/TheCannon) [Cannon](https://github.com/annayqho/TheCannon) - a data-driven method for determining stellar parameters and abundances from stellar spectra.
 - [The Payne](https://github.com/pacargile/ThePayne) - Artificial Neural-Net compression and fitting of synthetic spectral grids.
 - [PSOAP](https://github.com/iancze/PSOAP) - Tools for data-driven spectra models with Gaussian processes. Pronounced "soap."
 - [pydis](https://github.com/jradavenport/pydis) - A simple longslit spectroscopy pipeline in Python
 - [pyspeckit](https://github.com/pyspeckit/pyspeckit) - Python Spectroscopic Toolkit
 - [sick](https://github.com/andycasey/sick) - the spectroscopic inference crank
 - [Specmatch Empirical](https://github.com/samuelyeewl/specmatch-emp) - tool to extract the fundamental properties (effective temperature, radius, and metallicity) by comparing a target star's spectrum to a library of spectra from stars with known properties.
 - [Specmatch Synthetic](https://github.com/petigura/specmatch-syn) - tool to extract the fundamental properties (effective temperature, radius, and metallicity) by comparing a target star's spectrum to synthetic spectra.
 - [specviz](https://github.com/spacetelescope/specviz) - An interactive astronomical 1D spectra analysis tool.
 - [specutils](https://github.com/astropy/specutils) - Astropy affiliated package for 1D spectral operations.
 - [splat](https://github.com/aburgasser/splat) - SpeX Prism Spectral Analysis Toolkit
 - [Starfish](https://github.com/iancze/Starfish) - Tools for Flexible Spectroscopic Inference
 - [TelFit](https://github.com/kgullikson88/Telluric-Fitter) - Telluric fitting made easy
 - [wobble](https://github.com/megbedell/wobble) - Precise data-driven RV fitting, now with tellurics!

#### Photometry and source detection

 - [image registration](https://github.com/keflavich/image_registration) - Image Registration for Astronomy.
 - `julia`[Celeste.jl](https://github.com/jeff-regier/Celeste.jl) - Scalable inference for a generative model of astronomical images.
 - [Dust Maps](https://github.com/gregreen/dustmaps) - A uniform interface for a number of 2D and 3D maps of interstellar dust reddening/extinction.
 - [fsps](https://github.com/cconroy20/fsps) - Flexible Stellar Population Synthesis
 - [LA Cosmicx](https://github.com/cmccully/lacosmicx) - A fast implementation of the LA Cosmic algorithm
 - `R` [ProFound](https://github.com/asgr/ProFound) - Source finding and extraction
 - [PSFutils](https://github.com/spacetelescope/psfutils) - Open-source Python package to provide convenience tools for working with point-spread functions.
 - [Synphot](https://github.com/spacetelescope/synphot_refactor) - Synthetic photometry using Astropy
 - [NOAO Source Catalog](https://github.com/dnidever/noaosourcecatalog) - Source catalog of all NOAO imaging data
 - [sep](https://github.com/kbarbary/sep) - Python and C library for source extraction and photometry
 - [sewpy](https://github.com/megalut/sewpy) - Source Extractor Wrapper for Python

#### Visualization

- [astro_animations](https://github.com/zingale/astro_animations) - Various animations used for teaching introductory astronomy concepts
- [gifsicle](https://github.com/kohler/gifsicle) - Create, manipulate, and optimize GIF images and animations
- [holoviews](https://github.com/ioam/holoviews) - Stop plotting your data - annotate your data and let it visualize itself.
- [aplpy](https://github.com/aplpy/aplpy) - Astronomical Plotting Library in Python
- [spectrify](https://github.com/labjg/spectrify) - Reverse engineer astronomical spectra into pretty rainbow pictures with Python
- [ztv](https://github.com/henryroe/ztv) - An astronomical image viewer written in Python.

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
- [kali](https://github.com/AstroVPK/kali) - A library to model a time series as a Continuous-time ARMA process

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

*Planet Search / Characterization*


- [PyTransit](http://github.com/hpparvi/PyTransit) - Fast and easy transit light curve modeling using Python and Fortran.
- [batman](http://github.com/lkreidberg/batman) - Fast transit light curves models in Python.
- [ktransit](http://github.com/mrtommyb/ktransit) - A simple exoplanet transit modeling tool in python
- [planetplanet](http://github.com/rodluger/planetplanet) - A general photodynamical code for exoplanet light curves
- [ketu](http://github.com/dfm/ketu) - I can haz planetz?
- [ttvfast-python](http://github.com/mindriot101/ttvfast-python) - Python interface to the TTVFast library
- `fortran` [TTVFast](https://github.com/kdeck/TTVFast) - TTVFast efficiently calculates transit times for n-planet systems and the corresponding radial velocities.
- [terra](http://github.com/petigura/terra) - Transit Detection Code
- [pysyzygy](http://github.com/rodluger/pysyzygy) - A fast and general planet transit (syzygy) code written in C and in Python
- [k2ps](http://github.com/hpparvi/k2ps) - K2 Planet Search
- [lcps](http://github.com/matiscke/lcps) - A tool for pre-selecting light curves with possible transit signatures
- [PyOrbit](https://github.com/LucaMalavolta/PyORBIT) - PyORBIT: a code for exoplanet orbital parameters and stellar activity.
- [exocartographer](https://github.com/bfarr/exocartographer) - A forward-modeling tool for constraining surface maps orbital parameters of exoplanets from time-resolved photometry
- [Spiderman](https://github.com/tomlouden/SPIDERMAN) - A fast code to simulate secondary transits and phase curves
- [ExoCTK](https://github.com/ExoCTK/ExoCTK) - The Exoplanet Characterization Tool Kit, an open-source, modular data analysis package focused primarily on atmospheric characterization of exoplanets


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
- [Gaia Archive](https://www.cosmos.esa.int/web/gaia/data) - Gaia data for one billion stars.
- [GALEX SQL query](http://galex.stsci.edu/casjobs/) - Galex data.
- [Hipparcos](http://heasarc.gsfc.nasa.gov/W3Browse/all/hipparcos.html) - Subset of HYG.
- [HYG](http://www.astronexus.com/hyg)- Database containing all stars in Hipparcos, Yale Bright Star, and Gliese catalogs (almost 120,000 stars, 14 MB).
- [LINEAR](http://www.astro.washington.edu/users/ivezic/linear/PaperIII/PLV.html) - 7194 LINEAR variables with light curve classification.
- [MAST](https://archive.stsci.edu/) - The Mikulski Archive for Space Telescopes houses astronomical data sets in the optical, ultraviolet, and near-infrared parts of the spectrum
- [NOAO Data Lab](https://datalab.noao.edu/) -  Offers large datasets now being generated by instruments on NOAO and other wide-field telescopes.
- [OGLE](http://ogledb.astrouw.edu.pl/~ogle/CVS/) - Variable stars towards OGLE-III fields in the Magellanic Clouds and Galactic bulge
- [Open Astronomy Catalogs](https://astrocats.space) - Databases of supernovae, tidal disruptions, kilonovae, and high-velocity stars.
- [Open Exoplanet Catalogue](https://github.com/OpenExoplanetCatalogue) - An open source database of all discovered extrasolar planets.
- [Research-based Science Education for Undergraduates](http://rbseu.uaa.alaska.edu/index.html) - Curated datasets on 7 projects designed for undergraduates.
- [SDSS SQL query](http://skyserver.sdss.org/dr12/en/proj/advanced/hr/sql.aspx) - Sloan Digital Sky Survey.
- [SDSS for Teachers](http://cas.sdss.org/dr5/en/proj/teachers/) - Includes basic projects and advanced projects
- [Supernova Cosmology Project](http://supernova.lbl.gov/union/) The Union2.1 SN Ia compilation of 883 SNe from 19 datasets.

### Future Datasets

- [ARCHES](http://www.arches-fp7.eu/index.php/tools-data/accessing-data) - XMM-Newton cross match database
- [Pan-Starrs](http://ipp.ifa.hawaii.edu/index.php) - Public data release coming soon.
- [SpaceXDB](https://www.spacexdb.cf) - Collection of SpaceX telemetries analysis, also i made a repository with all the [data](https://github.com/R4yGM/SpaceDB-Api)

### Social Media

- [Astronomer's Facebook Group](https://www.facebook.com/groups/123898011017097/) - Closed group for professional astromers, with over 8000 members.
- [Astronomers on Twitter](http://truesciphi.org/ast.html) - List of Astronomers on Twitter with over 1000 followers.
- [Astromers.io](http://astronomers.io/) - "A nice place for astronomers, and those working in the sphere of professional astronomy"
- [Community.lsst.org](https://community.lsst.org) - A community forum for using/developing LSST software and doing science with LSST.
- [Python Users in Astronomy](https://www.facebook.com/groups/astropython/) - A closed group for python users in astronomy.

****

Licensed [Creative Commons Zero](LICENSE).

[This exists because they told me to do it.](https://twitter.com/exoplaneteer/status/600452917779308544)

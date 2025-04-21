# CEI logo
> What started as a fun example of Wakis flexible 2d and 3d plotting capabilities to update the CERN-ABP-CEI section logo, turned out to be the perfect example to follow the full impedance assessment workflow using our in-house tools: `Wakis`, `BIHC`, `Iddefix` and `neffint`. This repository contains python notebooks 001-005 that provide a comprehensive and hands-on playground on wakefield and impedance related calculations.

## Getting started
You can install wakis from GitHub to have the latest changes into your conda environment:
```bash
pip install wakis['notebook']
```
or 
```
pip install git+https://github.com/ImpedanCEI/wakis.git@main
```

That's it! Now you can run the notebooks `001-005` and familiarize with our impedance ecosystem -and why not also generate your own version of the CEI logo :heart:

* :file_folder: **stl/** contains the geometry of the cavity and the letters for the logo
* :file_folder: **img/** contains some example images you can generate. Your simulation results will be generated there
* :file_folder: **results_wlXX/** contains some Wakis pre-computed results to be used in notebooks 003-005

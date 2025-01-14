# Code for producing GCM output for use with NASA's Planetary Spectrum Generator

## Introduction 

Currently produces .gcm binary files for upload to the PSG website.

For a much more complicated version which uses PSG locally in Docker, contact Greg Cooke at gjc53@cam.ac.uk.

## Instructions

Choose star, planetary parameters, observation type, observation units, whether clouds are included.

The chemistry and parameters required for a baseline case where Earth-like biosignatures are the following:

'O3', 'O', 'O1D', 'OH', 'O2', 'H2O', 'CH4', 'CO2', 'T', 'CO', 'HNO3', 'N2O', 'CLDICE', 'CLDLIQ', 'ASDIF', 'ASDIR', 'ALDIF', 'ALDIR', 'SSAVIS', 'SSAVISdn', 'H2O2', 'NO','NO2','PS', 'TS','U','V'


## Questions to ask yourself about the setup

* Has the planet been defined relative to the star correctly?
* Has the observer been defined relative to the system correctly?
* Is the distance to the system correct?
* Are you using a coronagraph? If so, is the orbit actually observable?
* Do I know where the substellar point is for each file?
* What is the inclination angle of the observation?
* What are LMAX and NMAX and how do they effect my results?
* Are you interested in noise? If so, are all parameters reasonable and realistic?
* What is the spectral type of the star?
* What is the size of the planet and the size of the star? Do these match the simulations?
* What is the observation time?
* Is there any exozodiacal dust?

## Questions to ask yourself about the results

* How do they compare to other results in the literature?
* What is each feature due to? A molecule, the temperature, or scattering?
* Do the results make sense in the context of the planet-star system?
* Are the noise estimates realistic?

  

 

# NLTE inversions of Stokes profiles using Artificial Neural Networks
## Introduction
We trained an ANN in order to map sets of atmosphere magnitudes to their corresponding Stokes profiles. This model is later used to generate fast NLTE inversions of measured profiles.

## Data used (private)
Two FITS files containing sets of atmosphere magnitudes (temperature, pressure, LOS and microturbulent velocity and magnetic field intensity, inclination and azimuth) and Stokes profiles (I, Q, U, V) in float64 format. Their dimensions are (61, 288, 288, 7) and (601, 288, 288, 4) respectively.

## Technologies
Jupyter Notebook (server version 6.0.1) <br />
Python 3 (version 3.7.4)

## Repository contents
* data-visualization.ipynb <br />
Notebook with different graphic representations of the data.

* main-code.ipynb <br />
Notebook with the code used to create, train and use the ANN for inversions.

* dissertation.pdf <br />
Text file with a complete description of the project.

* presentation.pptx <br />
PowerPoint slides used in the presentation of the project.


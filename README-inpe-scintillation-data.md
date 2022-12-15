# INPE scintillation data example

This is an example data for the papers:

* Sun, K. A., Pi, X., Rino, C., & Lee, J. (2022). Statistical Uncertainty in the frequency dependence of the intensity scintillation index (S4). *Space Weather*, (Submitted)

## Description of the data

The data was obtained from Septentrio PolaRxS Pro GNSS receivers at five stations: FRTZ (3.73S, 38.72W), PALM (10.20S, 48.31W), POAL (30.07S, 51.12W), PRU2 (22.12S, 51.41W), and SJCE (23.21S, 45.86W) from November 2013 to January 2014.
The phase screen parameters: the scattering strength (U), spectral index (p), and Fresnel frequency (fF) are extracted via iterative parameter estimation (IPE) method.
Further details about the IPE method can be found in Carrano et al. (2017).

* Carrano, C. S., Rino, C. L., & Groves, K. M. (2017). Maximum Likelihood Estimation of Phase Screen Parameters from Ionospheric Scintillation Spectra. Proc. 15th IES Symposium, Alexandria, VA.

### Variables

```
INPE_refined.mat

column 1 U (scattering strength)
column 2 p (one-component phase spectral index)
column 3 fF (Fresnel frequency)
column 4 S4(f_L1) with a 30-min window
column 5 S4(f_L2) with a 30-min window
column 6 S4(f_L1) with a 1-min window
column 7 S4(f_L2) with a 1-min window

```

## Online Repository link

* [DataRepository](https://github.com/kiyoungsun/INPE-scintillation-data) - Link to the data repository.

## Acknowledgments

* The scintillation dataset used in this study was collected by Dr. Eurico de Paula at INPE (Instituto Nacional de Pesquisas Espaciais), Brazil.

# Processed resultsof a INPE scintillation dataset

Here are the processed results used in the paper:

* Sun, K. A., Pi, X., Rino, C., & Lee, J. (2023). Statistical Uncertainty in the frequency dependence of the intensity scintillation index (S4). *Space Weather* (Submitted)

## Description of the data

The data was obtained from Septentrio PolaRxS Pro GNSS receivers at five stations: FRTZ (3.73S, 38.72W), PALM (10.20S, 48.31W), POAL (30.07S, 51.12W), PRU2 (22.12S, 51.41W), and SJCE (23.21S, 45.86W) from November 2013 to January 2014.
The phase screen parameters: the scattering strength (U), spectral index (p), and Fresnel time scale (rhoF/veff) are extracted via iterative parameter estimation (IPE) method.
Further details about the IPE method can be found in Carrano et al. (2017).

* Carrano, C. S., Rino, C. L., & Groves, K. M. (2017). Maximum Likelihood Estimation of Phase Screen Parameters from Ionospheric Scintillation Spectra. Proc. 15th IES Symposium, Alexandria, VA.

### Variables

```
INPE_processed.mat

column 1 yymmdd
column 2 station number (1: FRTZ, 2: PALM, 3: POAL, 4: PRU2, 5: SJCE)
column 3 sat_id
column 4 Epoch in UT (s)
column 5 U (scattering strength)
column 6 p (one-component phase spectral index)
column 7 rhoF/veff (Fresnel time scale)
column 8 S4(f_L1)
column 9 S4(f_L2)

```

## Online Repository link

* [DataRepository](https://github.com/kiyoungsun/INPE-scintillation-data) - Link to the data repository.

## Acknowledgments

* The scintillation dataset used in this study was collected by Dr. Eurico de Paula at INPE (Instituto Nacional de Pesquisas Espaciais), Brazil.

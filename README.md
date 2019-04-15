# Spectral empirical orthogonal function analysis of reanalysis data in Matlab

The scripts contained in this contribution compute the spectral empirical orthogonal function (SEOF) decomposition of reanalysis data. The examples include the weather and climate patterns discussed in reference [1], namely the Madden-Julian Oscillation (MJO), the Quasi-Biennial Oscillation (QBO), and the El Nino-Southern Oscillation (ENSO). These patterns are educed from ERA-Interim and ERA-20C data that must be downloaded separately. The corresponding Python scripts are located in the 'data/EI' (ERA-Interim) and 'data/E20C' (ERA 20C) folders. Please refer to https://confluence.ecmwf.int/display/WEBAPI/Access+ECMWF+Public+Datasets for details on how to set up an account with ECMWF and download their public datasets. The core routine spod() that performs the SEOF decomposition (called SPOD in fluid mechanics) is located in the 'utils' folder. The most recent version and more information and examples can be found under https://www.mathworks.com/matlabcentral/fileexchange/65683-spectral-proper-orthogonal-decomposition-spod.

# Cite as
[1] O. T. Schmidt, G. Mengaldo, G. Balsamo and N. P. Wedi
"Spectral Empirical Orthogonal Function analysis of weather and climate
data", Monthly Weather Review, 2019

M0EYT data analysis of TIANWEN-1 2020-10-27 UTC

M0EYT supplies Doppler data in the following format:
Date,Time,Frequency(Hz), Signal Level(dB)
Frequency is a downconverted value.  In this case -8000MHz.

Use the SpectraVue_converter_viewer.ipynb to convert from the rOOt SpectraVue format to Cees Bassa's STRF format:
MJD,Freq(Hz),signal level,COSPAR#

m0eyt.script is a GMAT 2020a script that generates range rate data needed by M0EYT_Doppler_study.ipynb to compare the received data with the calculated data based on the state vector in m0eyt.script.

# Aalto-implementations-for-flickermeter-and-SVM-meter
These files are the current version of Aalto flickermeter and two SVM meters for MATLAB.
These software require the waveform and the sampling frequency of said waveform as inputs.

May 6th 2024, we added zero-padding to the Aalto SVM meter, which dealt with some problems found in the original. This takes an extra input variabe (zp) where you can inidicate the amount of zero padding.
We recommend zp=15 as a starting point.

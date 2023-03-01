# HPL-EMG-Processing

This repository includes Matlab apps for visualization and analysis of HDsEMG data taken using Sessantaquattro+. It is primarily used by students and researchers in the Human Performance Laboratory of UNB Faculty of Kinesiology.

## EMGProcessing32x1.mlappinstall

This software processes data from an 8 x 4 HDsEMG grid. It takes a csv file as input. The csv file is a pre-processed using the OTBiolab+ software and should contain 34 columns. The first column is the time signal. Columns 2-33 are the EMG signals from the individual grids. Column 34 is the AUX (auxiliary) output.The auxiliary output may be an isokinetic dynamometer signal or a trigger signal. 


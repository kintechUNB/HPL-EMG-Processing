# HPL-EMG-Processing

This repository includes Matlab apps for visualization and analysis of HDsEMG data taken using Sessantaquattro+. It is primarily used by students and researchers in the Human Performance Laboratory of UNB Faculty of Kinesiology.

## EMGProcessing32x1.mlappinstall

This software processes data from an 8 x 4 HDsEMG grid. It takes a csv file as input. The csv file is a pre-processed using the OTBiolab+ software and should contain 34 columns. The first column is the time signal. Columns 2-33 are the EMG signals from the individual grids. Column 34 is the AUX (auxiliary) output.The auxiliary output may be an isokinetic dynamometer signal or a trigger signal. 

The output file is called EMGAnalysisResults.csv which contain the following columns:
* ParticipantNumber
* Muscle - the muscle involved (e.g. biceps, triceps)
* Sex - the biological sex
* Side - side involved (left or right)
* Task - a description of the task
* ARVmean - the mean of the Averaged Rectified Value in uV 
* RMSmean - the mean of the Root Mean Square value in uV 
* MNFmean - the mean of the Mean Frequenies  in Hz 
* MDFmean - the mean of the Median Frequencies in Hz
* Entropy - a measure of signal homogeneity
* CoV - coefficient of variation
* Xcg, Ycg - Heatmap centroid values

## Sample Files
There are two sample csv files for testing the app. Both sample files were taken using a sessantaquatro+ EMG system. The output file was processed to show 32 EMG channels and 1 auxiliary channel. Column 1 contains the timestamp, columns 2-33 are the EMG measurements, and column 34 contains the auxiliary output values. 

* <b>SampleFile_Isokinetic.csv</b> - auxiliary output from CSMI isokinetic dynamometer with ramped torque values.
* <b>SampleFile_trigger.csv</b> - auxiliary output from a 5V DC source to identify start and stop points of a functional task. 

## Installation instructions
1. Download the mlappinstall file. 
2. Save the mlappinstall file in computer's Matlab folder
3. Double click the file to install it in Matlab's Apps tab. Follow prompts to install.
4. For easier access, add the app to favorites by clicking the star. Rearrange your favorite apps to show this app first.
5. Have fun analyzing! 

## For bugs or improvement suggestions
Contact: <a href = "mailto: joel.tabarangao@unb.ca">Joel Tabarangao </a> 

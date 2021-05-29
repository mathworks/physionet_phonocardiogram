# physionet_phonocardiogram
This repository contains human phonocardiogram (PCG) data used in MathWorks' Wavelet Toolbox machine and deep learning examples. This data is sourced from https://www.physionet.org/challenge/2016/. In keeping with PhysioNet's copying policy, the PCGData.zip file contains a .txt file, Modified_physionet_data.txt, which contains the specific attributions for the orignal PhysioNet source files as well as a description of all data modifications.

Important Note:
Examples in some versions of MATLAB reference the downloaded .zip file in text and code as ending in ```-master.zip```. To avoid errors in 
execution, replace instances of ```-master.zip``` in code with ```-main.zip```.

For example:

``>>unzip(fullfile(tempdir,'physionet_phonocardiogram-main.zip'),tempdir)``

``>>unzip(fullfile(tempdir,'physionet_phonocardiogram-main','PCG_Data.zip'),...``

``    fullfile(tempdir,'PCG_Data'))``

If you use ```git clone https://github.com/mathworks/physionet_phonocardiogram``` to download the data, the .zip file is "PCG_Data.zip" in your
physionet_phonocardiogram folder.

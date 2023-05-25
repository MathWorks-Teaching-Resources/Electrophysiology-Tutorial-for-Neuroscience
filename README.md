[![View Electrophysiology-Tutorial-for-Neuroscience on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/86972-electrophysiology-tutorial-for-neuroscience)

# ELECTROPHYSIOLOGY TUTORIAL FOR NEUROSCIENCE

This is a MATLAB tutorial for neuroscientists analyzing neural signals recorded during electrophysiology experiments. In addition to data recorded from electrodes placed within the brain, this also includes EEG and ECoG signals.
  
The tutorial is a step by step guide through the key principles of neural signal analysis using a snippet of pre-recorded data. It illustrates the use of timetables, filtering, pca, clustering using Gaussian mixture models, power spectra and time frequency analyses (spectrogram).
  
Apart from demonstrating all these steps programatically, the tutorial also points to the Signal Analyzer App at appropriate points.

For the tutorial to run, the neural_data.mat file is required

To run this tutorial, the following are required
1. MATLAB, the Signal Processing and the Statistics and Machine Learning Toolboxes. These can be accessed via a school or institution's license or a free trial may be downloaded from https://www.mathworks.com/campaigns/products/trials.html
2. the accompanying file neural_data.mat which should be in the same folder as the Live Script

To run it with your own data, do the following
1. make a copy of the file neural_data.mat, saving it under a different name 
2. create your own file neural_data.mat which contains two variables
    a. data: an numeric array of voltage values 
    b. fs: a scalar denoting the sampling frequency in Hz





# Preprocessing of EEG raw data for hypothesis testing and predictive modeling
 
This is a fundamental pipeline for semi-manual pre-processing of EEG (ElectroEncephalyGraphic) data, using the MNE-python package (https://mne.tools/stable/index.html).

It includes the following stages:

* Reading .edf file containing raw EEG + triggers channel.
* Performing visual inspection of the data and interactively marking movement artifacts and bad electrodes.
* Removing eye blinks and heart-beat traces by decomposing and recomposing the signal using Independent Component Analysis (ICA).
* Final inspection of the clean data, and saving.

This script is set as a tutorial, with 1 example data file.
Data file: 'Example_data.edf'

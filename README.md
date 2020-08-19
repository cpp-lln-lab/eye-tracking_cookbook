# Eye-tracking resources (or: How I learned to stop worrying and love the Eye-Tracker)

This repo will help to understand how to set your experiment with the Eye-Tracker (for the moment Eye-Link 1000) and analyze the output in a thoughtful way. Its main goal is to gather together information/guides/links/codes/etc. .

## TO DO

- [ ] extracting the function used by fieldtrip to convert the ascii output from the eyelink into a tsv file.

## Connect with the Eye Tracker computer

## Setting up your experiment

### PTB Eye-Tracker implementation

- cpp-lln-lab/CPP_PTB (what else!)

- see also:
  - Cornelissen, F. W., Peters, E. M., & Palmer, J. (2002). The Eyelink Toolbox: eye tracking with MATLAB and the Psychophysics Toolbox. Behavior Research Methods, Instruments, & Computers, 34(4), 613-617. [Web Version](https://link.springer.com/article/10.3758/BF03195489)

### EyeLink Manuals
- Eyelink1000_usermanual.pdf

## Output conversion

### edf to ASCI

- `edf2asc.exe` executable that converts the eye-tracker output from edf to ASCII format readable by MATLAB/R/Python, otherwise you will need DataViewer and its license key. It recquires windows OS.
- `edf2ascALL.m` script to apply `edf2asc.exe` to your edf files, as they come from the eye tracker. It recquires windows OS.

- examples of .edf files and its converted version to .asc

  - `eye_ExpIDMTlocUL_RunID1_SubIDRoBo.edf`
  - `eye_ExpIDMTlocUL_RunID1_SubIDRoBo.asc`

### BIDS format

- fieldtriptoolbox
[Converting an example eye tracker dataset for sharing in BIDS](http://www.fieldtriptoolbox.org/example/bids_eyetracker/)

- bids-standard/bids-validatore#990
[Why are "physio.tsv.gz" and its JSON currently not valid for eeg/meg/ieeg ? #990](https://github.com/bids-standard/bids-validator/issues/990)

- BIDS Eye Tracking
[BIDS Extension Proposal 20 (BEP020): Eye Tracking including Gaze Position and Pupil Size](https://docs.google.com/document/d/1eggzTCzSHG3AEKhtnEDbcdk-2avXN6I94X8aUPEBVsw/edit)

## Analyze your data

### DataViewer
- Eyelink_DataViewer.pdf

### Open source packages

[Researcher Contributed Eye Tracking Tools](https://github.com/davebraze/FDBeye/wiki/Researcher-Contributed-Eye-Tracking-Tools)

#### MATLAB

- [Edf2Mat© Matlab Toolbox](https://github.com/uzh/edf-converter) Converts EyeLink 1000 Edf files into Matlab & fast analysis

#### Python

- [Cili](https://github.com/beOn/cili)

- [PyGaze](https://github.com/esdalmaijer/PyGaze)

#### R

- [edfR](https://github.com/jashubbard/edfR)

- [eyelinker](https://github.com/dahtah/eyelinker)

### other

- [Remi-Gau/AVT_eye_tracker](https://github.com/Remi-Gau/AVT_eye_tracker)
- Eyetracker Output Utility Manual.pdf

# Eye-tracking resources (or: How I learned to stop worrying and love the Eye-Tracker)

This repo will help to understand how to set your experiment with the Eye-Tracker (for the moment Eye-Link 1000) and analyze the output in a thoughtful way. Its main goal is to gather together information/guide/code/etc. .

## Setting up your experiment

### Manuals
- Eyelink1000_usermanual.pdf
- Eyelink_DataViewer.
- Eyetracker Output Utility Manual.pdf

## Analyze your data

### Output conversion

- `edf2asc.exe` executable that converts the eye-tracker output from edf to ASCII format readable by MATLAB/R/Python, otherwise you will need DataViewer and its license key. It recquires windows OS.
- `edf2ascALL.m` script to apply `edf2asc.exe` to your edf files, as they come from the eye tracker. It recquires windows OS.

- examples of .edf files and its converted version to .asc

  - `eye_ExpIDMTlocUL_RunID1_SubIDRoBo.edf`
  - `eye_ExpIDMTlocUL_RunID1_SubIDRoBo.asc`

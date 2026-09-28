# 🧠 EEG Data Analysis Hackathon

Welcome! 
This repository contains presentations, practice sheets and solutions for the EEF Hackathon organized by the Student Network for Neuroscience (SNN) in early 2026.
All content has been created by members of the organizing team of the SNN, and is therefore provided from students, for students.

The Hackathon covers the basics of how to import and preprocess EEG Data using Python MNE, while also providing some theoretical insights into EEG in general, and the different preprocessing steps. 

Prior expereince programming with Python is helpful, but not strictly necessary.

## The Data
This Hackathon comes with a small EEG Dataset, which were recorded at an accompanying Hands-On EEG Workshop by the Student Network for Neuroscience. 
Disclaimer: the Data is solely for practice purposes, and not fit to be used in any kind of scientific analyses. It also may be a bit noisier than EEG data you would acquire in a regular Lab, due to the setting in which it was recorded.

You can download the data here: https://openneuro.org/datasets/ds007813

## 📂 Repository Structure
### _python_setup
If you are not familiar with Python or programming in general, here you will find a brief guide for the necessary installations.
Documents are numbered in the order in which they should be read.
If the instructions in these guides are not sufficient to you - as they are rather short - simply search for a beginner introduction to Python and Virtual Environments. Almost any guide will largely cover the same content.

### tasksheets
In this folder you will find jupyter notebooks (.ipynb files) with the coding steps. Each step comes with some explanations / tips etc. 
Generally, all task are reather closely aligned to the introductory guide provided by Python MNE - we recommend going through that guide & the package documentation while working on the tasksheets, instead of relying on AI, as this will give you a better insight and understanding  into how this package works.
The Python MNE documentation: https://mne.tools/stable/index.html

The tasksheet_short_ver is a abbreviated version of the other 3 sheets, created for a shorter version of the Hackathon.

### solutions
Here you will find exemplary solutions for all four tasksheets. You can use them to check your own code against. If you want to run these scripts, please keep in mind that you will need to adjust the path variables to the data. 

# fys5429-project2 - Use of parameterized networks in search for SUSY particles

This repo belongs to a project in FYS5429, Advanced machine learning and data analysis for the physical sciences. The aim of this repo is the study of SuperSymmetry simulations from AtlasOpenData. First all the data is recieved from Atlas, 
then a neural network (NN) is designed to tackle the problem of free parameters in the physics model, to classify SUSY and background events(binary classification)

A counting analysis is then used to analyse the NN output. A new approach has been taken to tackle the issue of free mass parameters, instead of training multiple NN's, one large NN was trained with the ability to interpolate between mass values. This apprach makes searches for new physics easier.

To recieve the data, Opendata_lep.ipynb has to run. In this file we extract 2lep events from the open data, and select a number of features. 

Once the data is avaliable, PNN.ipynb can run, in this file the data is opened and prepared for the neural network training. Analysis.ipynb is used for the counting experiment, and exclusion plots. 

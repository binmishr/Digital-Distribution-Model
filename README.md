# Digital-Distribution-Model

There has been three data files are attached to this repository :

i) speed_acc.RData

ii) brms_DDM_example_fit.rda

iii) brms_DDM_example_predictions.rda

Kindly refer them while making the Digital Distribution Model Analysis.

Please find below the description about each data files. You can use the App RStudio to view the file after downloading to your PC.

i) speed_acc.RData
===================
Description : Responses and response times from an experiment in which instruction manipulated speed and accuracy between blocks.

Usage : speed_acc or data(speed_acc)

Format : A data.frame with 32,032 obs. and 9 variables:

Variables are described below:
==============================
id : participant id

block : block number

condition: accuracy for blocks with accuracy instructions; speed for blocks with speed instruction

stim: unique identifier of stimulus, stimuli are nested in frequency conditions

stim_cat :category of stimulus, either word or non-word

frequency : "high frequency word", "low frequency word", "very low frequency word", or non-words derived from the first three categories

response :word, nonword, or not interpretable response (error, i.e., pushed a button, but not the right one and also not the one next to the right button)

rt :response time in seconds

censor :boolean indicating whether or not a response should be eliminated prior to analysis; uninterpretable response, too fast response (<180 ms), too slow response (>3 sec)

Details:
===========
The data excludes the practice blocks but includes all trials. Variable censor can be used for excluding all trials also excluded from the papers using it namely uninterpretable response, too fast response (<180 ms), too slow response (>3 sec). Heathcote and Love (2012, p. 7) describe the data as follows:

These lexical decisions were made about four types of stimuli, non-words (nw) and high-frequency (hf), low-frequency (lf), and very low-frequency (vlf) words. The data are speed or accuracy emphasis instructions in different experimental blocks. Accuracy blocks were preceded by the message "Try to respond accurately" and "ERROR" was displayed after each wrong response. Speed blocks were preceded by the message "Try to respond accurately" and "TOO SLOW" was displayed after each response slower than 0.75 s.

ii) brms_DDM_example_fit.rda
=============================

Description: fitted model object data as fitment data.

iii) brms_DDM_example_predictions.rda
======================================

Description : Posterior predictive distributions data of the model.

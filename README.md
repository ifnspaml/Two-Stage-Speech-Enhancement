# Two-Stage-Speech-Enhancement

This page contains supplementary material for the paper "Speech Enhancement by LSTM-Based Noise Suppression Followed by CNN-Based Speech Restoration". 

 ## Audio Demos
 - Audio demos for our proposed two-stage speech enhancement system and several reference methods are provided under `./Audio_Demo/`.
 - All the audio demos use files from the test dataset in the presence of unseen noise conditions at a signal-to-noise ratio (SNR) of 5 dB. The audios include speech from both female and male test speakers.
 - The unseen noise files are taken from the ETSI background noise database, which is a completely unseen database for our system (no noises from the ETSI database have been seen in training).
 - Audio examples are provided using “Pub Noise”, “Office Noise”, and “Traffic Noise” conditions. Please note that the training of our model focuses on non-stationary noise types including interfering speech and the “Traffic Noise” example shows the generalization performance on a noise type not including interfering speech.



# speech_technology_projects
this repository contains codes for digit recognition and text-dependent speaker recognition codes 

## Project 2: DIGIT RECOGNITION
We trained a Gaussian Mixture Model (GMM) for mfcc features for each digit from pre-recorded data for numbers that span 0 to 9. We trained the GMM model for 32 components in this case.

## Project 4: TEXT DEPENDENT SPEAKER RECOGNITION
For mfcc feature vectors derived from wav files, DTW-based speaker verification with and without GMM posteriogram(8 components) mapping was performed. Because the values for training GMM posteriograms are so tiny and entail exponential values, we used DTW between normalized log values of computed GMM posteriorgrams.

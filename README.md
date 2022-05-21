# Starbucks_Recommendation_FunkSVD
## Blog link
https://medium.com/@olubodem/starbucks-offer-recommendation-bd399e79bfb8

## Libraries used
The following are the libraries used in the project
pandas as pd
numpy as np
math
json
matplotlib.pyplot as plt
seaborn as sns
tqdm for progress bar visualization
from tqdm import notebook, trange

## Project Motivation
The motivation of the project is to identify target audience of promotional offers. Promotional offers encourage customers to make
more purchases and they usually come with conditions for certain rewards to be won over some time limitations.
This project is aimed at identifying ideal candidates for promotional offers for a Starbucks product.

## Files in the repository
Data folder contains the input files for the analysis. Profile contains the demographic data of users, portfolio holds information about 
the offers under consideration and transcript holds information about customer's transactions and interactions with offers received

.gitignore contains rules to prevent pushing jupyter notebook checkpoints files to remote

Starbucks_Capstone_notebook.ipynb is the jupyter notebook where the analysis is done

pic1 and pic2 are pictures used in the problem description.

## Summary of Results
FunkSVD was used to predict the completion of an offer by a client with an accuracy of 69% compared to the naive model with an
accuracy of 31%.

## Acknowledgement
Thanks to Starbucks for making the data available for this project, and to Udacity for providing this platform (Nanodegree) to learn and practice.

# Deep-Learning-Predicting-Census-Income:

# Project Overview: 

- Prediction task is to determine whether a person makes over 50K a year.

# Project Description: 

- This data was extracted from the census bureau database found at:
http://www.census.gov/ftp/pub/DES/www/welcome.html
- Split into train-test using MLC++ GenCVFiles (2/3, 1/3 random).
- 48842 instances, mix of continuous and discrete    (train=32561, test=16281)
- 45222 if instances with unknown values are removed (train=30162, test=15060)
- Duplicate or conflicting instances : 6
- Class probabilities for adult.all file
- Probability for the label '>50K'  : 23.93% / 24.78% (without unknowns)
- Probability for the label '<=50K' : 76.07% / 75.22% (without unknowns)
- A set of reasonably clean records was extracted using the following conditions:
   ((AAGE>16) && (AGI>100) && (AFNLWGT>1)&& (HRSWK>0))
- Prediction task is to determine whether a person makes over 50K a year.

# Tested Skills:

- Apply Deep Learning models
- Use of H2O
- Compare the Deep Learning models
- Grid Search on Deep Learning models
- Tuning the accuracy in DL models
- Data Science 
- R 
- Hyperparameter Optimization 

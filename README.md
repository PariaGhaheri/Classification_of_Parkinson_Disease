# Diagnosis of Parkinson's Disease Based on Voice Signals Using SHAP and Hard Voting Ensemble Method
## Introduction
**Diagnosis of Parkinson's Disease Based on Voice Signals Using SHAP and Hard Voting Ensemble Method**

*Authors* : [Paria Ghaheri](https://www.linkedin.com/in/paria-ghaheri-534a44206/), [Hamid Nasiri](https://www.linkedin.com/in/hamid-nasiri-b5555487/), [Ahmadreza Shateri](https://www.linkedin.com/in/farbod-shateri-a75472252/), [Arman Homafar](https://www.linkedin.com/mwlite/in/homafar)

*Abstract* : Parkinson's disease (PD) is the second most common progressive neurological condition after Alzheimer's, characterized by motor and non-motor symptoms. Developing a method to diagnose the condition in its beginning phases is essential because of the significant number of individuals afflicting with this illness. PD is typically identified using motor symptoms or other Neuroimaging techniques, such as DATSCAN and SPECT. These methods are expensive, time-consuming, and unavailable to the general public; furthermore, they are not very accurate. These constraints encouraged us to develop a novel technique using SHAP and Hard Voting Ensemble Method based on voice signals. In this article, we used Pearson Correlation Coefficients to understand the relationship between input features and the output, and finally, input features with high correlation were selected. These selected features were classified by the Extreme Gradient Boosting (XGBoost), Light Gradient Boosting Machine (LightGBM), Gradient Boosting, and Bagging. Moreover, the Hard Voting Ensemble Method was determined based on the performance of the four classifiers. At the final stage, we proposed Shapley Additive exPlanations (SHAP) to rank the features according to their significance in diagnosing Parkinson's disease. The proposed method achieved 85.42% accuracy, 84.94% F1-score, 86.77% precision, 87.62% specificity, and 83.20% sensitivity. The study's findings demonstrated that the proposed method outperformed state-of-the-art approaches and can assist physicians in diagnosing Parkinson's cases.

This repository contains python source code of the following paper:

## Dataset

We used the "[Parkinson Dataset with Replicated Acoustic Features](https://archive.ics.uci.edu/ml/datasets/Parkinson+Dataset+with+replicated+acoustic+features+)" given to the Machine Learning repository at the University of California, Irvine, in April 2019 by Naranjo et al. 

In this dataset, characteristics are gathered by examining the sound recordings of 80 individuals (40: healthy, 40: PD). Three repetitions of a five-second-long phonation of the vowel /a/ were performed. The sampling rate for digital recordings was 44.1 kHz, and the sample size was 16 bits. The collected features were separated into various groups based on whether or not they share similar formulations. This segmentation yielded nine groups, four of which had a single characteristic.

**Attribute Information**
* Pitch local perturbation measures: relative jitter (Jitter_rel), absolute jitter (Jitter_abs), relative average perturbation (Jitter_RAP), and pitch perturbation quotient (Jitter_PPQ).
* Amplitude perturbation measures: local shimmer (Shim_loc), shimmer in dB (Shim_dB), 3-point amplitude perturbation quotient (Shim_APQ3), 5-point amplitude perturbation quotient (Shim_APQ5), and 11-point amplitude perturbation quotient (Shim_APQ11).
* Harmonic-to-noise ratio measures: harmonic-to-noise ratio in the frequency band 0-500 Hz (HNR05), in 0-1500 Hz (HNR15), in 0-2500 Hz (HNR25), in 0-3500 Hz (HNR35), and in 0-3800 Hz (HNR38).
* Mel frequency cepstral coefficient-based spectral measures of order 0 to 12 (MFCC0, MFCC1,..., MFCC12) and their derivatives (Delta0, Delta1,..., Delta12).
* Recurrence period density entropy (RPDE).
* Detrended fluctuation analysis (DFA).
* Pitch period entropy (PPE).
* Glottal-to-noise excitation ratio (GNE).

## Contact me
If you have any questions, do not hesitate to reach me via [Linkedin](https://www.linkedin.com/in/paria-ghaheri-534a44206/) or email: paria.ghaherii@gmail.com

Thank you so much for your attention.

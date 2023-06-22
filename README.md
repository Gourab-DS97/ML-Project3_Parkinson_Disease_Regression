# Machine Learning Regression Project : 
# Health Care Analytics- <br>Detection of Parkinson's Disease by vocal frequency analysis

## Abstract:
Parkinson's disease (PD) is a progressive disorder of central nervous system that affects movement of body parts controlled by the nerves. Almost 70%-90% of patients with PD shows an affected voice. Various studies revealed that voice is one of the earliest indicators of PD. 

## Objective:
<u>This project will predict UPDRS (Unified Parkinson's Disease Rating Scale) score based on the collected voice features</u>. UPDRS generally ranges from 0 to 176, with 0 corresponding to a healthy state and 176 to a severe affliction. The higher the score, the worse the parkinsonism.

## Description of Parkinson's Dataset:
The dataset contains a range of biomedical vocal measurements from people with early-stage Parkinson's disease through a telemonitoring device. The main aim of the data is to predict 'total_UPDRS' based on the 16 voice measures (starting from Jitter to PPE) as mentioned below.

## Dataset Source: 
UCI Machine Learning Repository

## Attribute Information:
* **subject#** - Serial Number <br>
* **age** - Patient's age<br>
* **sex** - Patient's gender '0': male, '1': female<br>
* **test_time** - Number of Times into trial. Integer part represents number of days <br>
* **total_UPDRS** - Clinician's total UPDRS score<br>
* **Jitter** - Measures of variation in fundamental frequency <br>
* **Shimmer** - Several measures of variation in amplitude <br>
* **NHR (Noise to Harmonies Ratio)** - measures of ratio of noise to tonal components in voice<br>
* **HNR (Harmonics to Noise Ratio)** - measures of ratio of noise to tonal components in voice<br>
* **RPDE (Recurrence Period Density Entropy)** - Dynamic complex measurement<br>
* **DFA (Detrended Fluctuation Analysis)** - Signal fractal scaling exponent<br>
* **PPE (Pitch Period Entropy)** - A nonlinear measure of fundamental frequency variation<br>

## Implementation of this Project in Real Life:
The first sign of PD is change in quality of voice: a reduced volume, monotone pitch etc. Since detection of early stages of Parkinson's Disease is very crucial, this project shows how assesment of voice can be used for day to day monitoring (local or remote) of PD patients. As a result, the entire screening process will be cost effective and also individual's quality of life can be improved through early treatment of this disease.

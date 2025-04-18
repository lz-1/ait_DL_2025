Title: El Nino-Southern Oscillation (ENSO) Prediction Using Neural Networks

Students: Lilian Zhu

Group: Anomaly Detection Aces

Project Description:
The El Nino-Southern Oscillation (ENSO) is an interannual cycle in the Pacific Ocean that happens every three to seven years, split into two phases: El Nino and La Nina. During El Nino, we experience a warm anomaly and decreased upwelling in the Eastern Pacific, as well as weakening of the easterly winds. During La Nina, we experience the opposite: cold anomalies, increased upwelling, and stronger easterlies. The NINO3.4 region is a region in the ocean that encompasses both El Nino and La Nina phases. The Oceanic Nino Index (ONI) is a three month rolling mean of sea surface temperature anomaly averaged across NINO3.4. These two phases are quantified in the following way:

ONI > 0.5 : El Nino and ONI < 0.5 : La Nina

Understanding ENSO and accurately predicting these phases are critical to knowing temperature and precipitation trends on Earth. These phases have global impacts beyond the tropical Pacific, and can affect economies across the globe. Therefore, we propose a convolutional neural network to predict the cycles of ENSO with the following input and output:

Input: We use sea surface temperature (SST) with time lags of 3 months up to two years as our channels to the CNN
Output: ONI

And the following Training/Validation/Testing structure:

Training and Validation

Data will come from the Community Earth System Model (CESM) which is an ensemble of 40 climate models from all around the world. We will use a total of 10 ensembles from CESM

9 for training and 1 for validation

Testing

We test our model on ERA5, a reanalysis climate product which is often used as a proxy for observations



Instructions:
How to acquire the data:
Data is accessed here:
https://www.cesm.ucar.edu/community-projects/lens2

I downloaded the data locally so I wouldn't need to pull from the server every time. The data is too large to put into Github. Here's is a google drive link to it:
https://drive.google.com/drive/folders/1R9ZXaIRMBmohVfNaAeBQJYGgiUgyojIq?usp=sharing

How to run the code:
Add the Google Drive folder with the data to your personal drive. Then when you mount google drive, the file path should go directly to the data as desired.

requirements.txt lists all python packages and their versions



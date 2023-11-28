# Singing Detection
The goal of the project is to develop a ML model which can detect and hard label an audio file with the regions where singing exists.

## Metrics for Test Data

1. **F1 Score - 99.97%** 
2. **Accuracy - 99.96%**
3. Loss = 0.0025


## Method

I first break the audio file into segments of 512 samples and obtain the input features for each segment. The input features are $MFCCs$, $ΔMFCCs$ and $Δ^2 MFCCs$ of the audio segment.

The ML model then classifies each segment as containing singing or not.



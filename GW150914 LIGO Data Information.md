# Project Overview

This project utilizes open data from ATLAS and a stochastic simulation to model the search for dark matter (https://opendata.cern.ch/record/atlas-93942). It does this by training a neural-network classifier that distinguishes signal events from Standard Model background. The model uses five kinematic variables—missing transverse energy, dilepton invariant mass, leading- and subleading-lepton transverse momentum, and dilepton angular separation. It includes class-imbalance weighting, hyperparameter optimization, learning-rate decay, ROC/AUC evaluation, and an optimized classification threshold.

---

# Results

---

# Advanced Model Evaluations

### SECTION 2: Strain Data

![strain](strain.png)---

### SECTION 4: Noise Spectrum
![noisespec](noisespec.png)---

### SECTION 5: The Whitening and bandpass filtering
![filtering](filtering.png)---

### SECTION 6: The Spectrogram
![specgram](specgram.png)---

### SECTION 7: Matched-Filter
![matchedfiler](matchedfilter.png)---

### SECTION 8: Results

```text
                    detector  our_peak_SNR our_peak_time_GPS  published_SNR published_merger_GPS  time_offset_from_published_s

0                         H1     25.926829      1.126259e+09           20.0         1.126259e+09                      0.000096
1                         L1     18.122539      1.126259e+09           13.0         1.126259e+09                     -0.007229
2         combined (network)     31.632687               NaN           24.0         1.126259e+09                           NaN

```

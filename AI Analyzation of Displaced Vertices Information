# Project Overview

This repository contains a standalone, open-source python research pipeline engineered to automate the isolation of exotic particle trajectories and long-lived displaced decay vertices. This project is directly inspired by the manual visual data-mining workflows presented to citizen scientists on the Zooniverse New Particle Search at CERN (https://zooniverse.org) initiative.

Rather than relying on human visual screening to look for lines crossing away from the primary interaction point, this application pairs a classical Hough Transform computer vision algorithm with a Deep Multi-Layer Perceptron (MLP) Neural Network to programmatically prune high-background noise and localize decay origins.

---

# Results

### SECTION 1: DISPLACED VERTEX SIMULATION
**Accuracy:** 98.68%

```text
Classification report:
              precision    recall  f1-score   support

  Background       1.00      0.98      0.99       120
      Tracks       0.94      1.00      0.97        32

    accuracy                           0.99       152
   macro avg       0.97      0.99      0.98       152
weighted avg       0.99      0.99      0.99       152
```

![Displaced Vertex Results](images/download.png)

### SECTION 2: MOMENTUM-SPACE SIMULATION
**Accuracy:** 81.00%

```text
Classification report:
              precision    recall  f1-score   support

      Signal       0.76      0.91      0.83      1000
  Background       0.89      0.71      0.79      1000

    accuracy                           0.81      2000
   macro avg       0.82      0.81      0.81      2000
weighted avg       0.82      0.81      0.81      2000
```

![Momentum-Space Results](images/download(1).png)

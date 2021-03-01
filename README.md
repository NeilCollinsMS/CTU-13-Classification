# CTU-13-Classification
Ongoing project to generate classification models that predict whether or not an IP address is a member of a Bot-Net.

Source Data: https://www.stratosphereips.org/datasets-ctu13

Per stratosphere suggestion, I will be utilizing bidirectional netflows over unidirectional netflows.

Per-Scenario predictions are using the RBF default 0.5 threshold for binary classification. Aggregate models will attempt to find the optimal threshold without overfitting the data. ROC AUCs will only be calculated for aggregate data models. Per-Scenario models are primarily for insight and exploration.

Formal Reference:
Garcia, Sebastian. Malware Capture Facility Project. Retrieved from https://stratosphereips.org

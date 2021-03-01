# CTU-13-Classification
Ongoing project to generate classification models that predict whether or not an IP address is a member of a Bot-Net.

Source Data: https://www.stratosphereips.org/datasets-ctu13

Per stratosphere suggestion, I will be utilizing bidirectional netflows over unidirectional netflows.

ROC AUCs and Threshold manipulation will be utilized in aggregate models, but per-scenario models are being used as baselines and will default to threshold = 0.5. 

Formal Reference:
Garcia, Sebastian. Malware Capture Facility Project. Retrieved from https://stratosphereips.org

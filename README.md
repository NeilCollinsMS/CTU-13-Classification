CTU-13-Classification
Ongoing project to generate classification models that predict whether or not an IP address is a member of a Bot-Net.

Source Data: https://www.stratosphereips.org/datasets-ctu13

Per suggestion, I will be utilizing bidirectional netflows over unidirectional netflows.

Per-Scenario predictions are using the RBF default 0.5 threshold for binary classification. Aggregate models will attempt to find the optimal threshold without overfitting the data. ROC AUCs will only be calculated for aggregate data models. Per-Scenario models are primarily for insight and exploration.

WARNING: CTU-13 (By Scenario) Models are largely useless, and were used to get my feet wet and avoid major pitfalls when aggregating data. Do not use these models.

Formal Data Reference:
Garcia, Sebastian. Malware Capture Facility Project. Retrieved from https://stratosphereips.org

If the aggregate workbook doesn't work, direct access link found here: https://colab.research.google.com/drive/1dpHUe-IhUJ_neXE4n9Mnw_3XMR6Wn5XO#scrollTo=y_GZgq8kso9s

Cleaned Data Access Link (Google Drive): https://drive.google.com/file/d/1MSopQ4ZZHqGNqdy619B-a3L2BTvEqK6m/view?usp=sharing

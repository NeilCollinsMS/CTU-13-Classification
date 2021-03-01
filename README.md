# CTU-13-Classification
Ongoing project to generate classification models that predict whether or not an IP address is a member of a Bot-Net.

Source Data: https://www.stratosphereips.org/datasets-ctu13

Note: Scenarios 1 & 12 do not have labeled unidirectional netflows available at this time. To maintain privacy, stratosphere does not provide full PCAP traces (only Bot Net exclusive traces), so I cannot use argus to generate my own classifiable netflow files. As such, Scenario 1 and Scenario 12 are being excluded from training & testing.

Formal Reference:
Garcia, Sebastian. Malware Capture Facility Project. Retrieved from https://stratosphereips.org

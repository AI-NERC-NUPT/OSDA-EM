# OSDA-EM
Implementation of Open Set Domain Adaptation with Entropy Minimization, 
submitted for possible publication and will be available soon.

# Prerequisites
These codes work on Tensorflow 1.3.0 and Python3.4

# Download
Dataset is BCIS, which should be downloaded and unzipped into ./dense_setup_decaf7,  place them into yourpath/data/

# Run
For the open set domain adaptation from BING to CALTECH256, you can run the experiment by the following steps:
1) modify the source_name and target_name in osda_em_BCIS as:
   source_name = "bing"         #from: sun, imagenet, caltech256, bing
   target_name = "caltech256"  #from: sun, imagenet, caltech256, bing
   
2) python3  osda_em_BCIS.py

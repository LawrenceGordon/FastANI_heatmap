# FastANI_heatmap
This repository contains Python code for building a heatmap and cladogram with the output of FastANI.

the Python code here can be run directly on the FastANI output file: https://github.com/ParBLiSS/FastANI

This code assumes everything has a pairwise comparison, but an optional line can be added at line 17 to say `data.fillna(X, inplace=True)` to fill with whatver value X you want.

The color break here is automatically determined by seaborn clustermap.

Example figure from the Python program showing some *Toxoplasma gondii* strain comparisons.

![testpy2](https://github.com/user-attachments/assets/7ff14bb7-c09a-451d-90c1-d7d3807b775e)

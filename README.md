# FastANI_heatmap
This repository contains Python code for building a heatmap and histogram with the output of FastANI.

the Python code here can be run directly on the FastANI output file: https://github.com/ParBLiSS/FastANI

This code assumes everything has a pairwise comparison, but an optional line can be added at line 17 to say `data.fillna(X, inplace=True)` to fill with whatver value X you want.

The color break here is automatically determined by seaborn clustermap.

Example figure from the R repository below with *Staphylococcus schleiferi* isolates. The python code gives similar results:

<img width="997" alt="heatmap" src="https://user-images.githubusercontent.com/43999021/133120697-10be7952-e8ca-4d4e-a300-3421d73e0127.png">


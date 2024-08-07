# Single-cell morphometrics reveals T-box dependent patterns of epithelial tension in the Second Heart Field

### Pipeline:
![fig1 scMorphometrics Pipeline (2)](https://github.com/user-attachments/assets/6951fcb8-b677-4888-80c1-f5e33ed7e2b1)

- Step 1: Perform Whole mount immunofluorescence on the Dorsal pericardial wall (the cardiac epithelium) using phalloidin to label the cell membranes and other proteins of interest.
- Step 2: Segment the images using Tissue Analyser (TA) as described by Aigouy et al.2016.
- Step 3: Quantification of features using TA, Force inference (Kong et al. 2019) and Dproj (Herbert et al. 2021).
- Step 4: Store,clean and merge the data to prepare it for machine learning algorithms.
- Step 5: Analyze the data using joint-spatial PCA (https://github.com/SoleneS/JointSpatialPCA) and furhter analysis.

### Goal: 
Understand the patterning of cardiac progenitors.The embryonic heart grows by the progressive addition of progenitor cells located on an epithelial layer known as the Dorsal pericardial wall (DPW).
T-box transcription genes (Tbx1 and Tbx5) play a key role in regulating the addition of the cells to the poles of the heart. However, the mechanisms by which the cells contribute to each pole remain unclear.

### To investigate this, we have:
Employed unsupervised clustering algorythms to map the cells according to their morphological features.

The data used for the analysis is stored in the Data folder. 




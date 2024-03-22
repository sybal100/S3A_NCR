# S3A_NCR
Scripts used for manuscript "Semaphorin-3A regulates liver sinusoidal endothelial cell porosity and promotes hepatic steatosis"

Fiji Plugin Analysis:
1. Scale images (only if your images are too large/not all the same size)
2. Image prep (images are adjusted)
3. Classification (using the trained WEKA classifier, the images are classified (fenestrae or no fenestrae))
4. Image quantification (the classified regions are measured and counted)
5. Classifier Model Using Contrast Images (For generation of probability maps)
6. Data Arff Using Contrast Images (For generation of high-contrast images)

Deep Learning Workflow Analysis:
1. Script for post-processing raw data files which are returned by the Segmentation tool

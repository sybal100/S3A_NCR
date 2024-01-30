# S3A_NCR
Scripts used for publication "XXX"

Fiji Plugin Analysis:
1. Scale images (only if your images are too large/not all the same size)
2. Image prep_ROI selection (images are adjusted and the region of interest can be chosen)
3. Classification (using the trained WEKA classifier, the images are classified (fenestrae or no fenestrae))
4. Image quantification (the classified regions are measured and counted)
5. Fiji Plugin Analysis (Script for post-processing raw data files which are returned by the Fiji Plugin for fenestrae quantification)

Deep Learning Workflow Analysis:
1. Script for post-processing raw data files which are returned by the Segmentation tool

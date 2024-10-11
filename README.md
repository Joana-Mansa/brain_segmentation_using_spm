# brain_segmentation_using_spm
This was group work and the output is a result of the combined efforts of my team member and me.
SPM (a GUI Matlab framework) was used to preprocess and skull-strip brain MRI NIFTI images. 
the probability maps (soft segments) derived from the SPM  were used in Google Colab notebook to convert them into volumes representing the main tissues (Cerebrospinal Fluid, Gray matter, and white matter). 
A ground-truth label was provided based on which, the dice score metric was calculated to evaluate the efficiency of our segmentation.


# brain_segmentation_using_spm
This was group work and the output is a result of the combined efforts of my team member and me.
SPM (a GUI Matlab framework) was used to preprocess and skull-strip brain MRI NIFTI images. 
the probability maps (soft segments) derived from the SPM  were used in Google Colab notebook to convert them into volumes representing the main tissues (Cerebrospinal Fluid, Gray matter, and white matter). 
A ground-truth label was provided based on which, the dice score metric was calculated to evaluate the efficiency of our segmentation.
The results show some skull-stripped brain tissue 


![image](https://github.com/user-attachments/assets/7ffb150f-520b-484b-acc1-35c9e9d1ac3c)

![image](https://github.com/user-attachments/assets/2d889bcb-3235-4b1b-8d7c-f8dba60224cb)




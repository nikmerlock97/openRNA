<!-- <h1 align="center"> openRNA </h1 -->
# openRNA

Open-source toolbox and workflows for automated analysis of RNAscope data from human and mouse

## Current Features
### Automated analysis of RNAscope data
  * Automated cell counting (currently works for TIF and CZI files only)
 
  * [Mouse](docs/mouse_vignette.md) and [Human](docs/human_vignette.md) workflows
  
    * Same matlab [toolbox](https://github.com/nikmerlock97/openRNA/tree/master/toolbox) is used for both data sets.
  

### Image-level and ROI-level (or nuclei-level) statistics
  * Outputs 2 CSVs after automated analysis of TIF or CZI file(s)
 
    * `man.csv` represents *image-level* summary statistics for each channel of input data
   
    * `longdat.csv` represents *ROI-level* (or *nuclei-level*) summary statistics for each channel of input data

  * These two CSVs can be read into R (or python, or Matlab, or your favorite statistical sofware tool). 

## Example: Before and After automated analysis
The input [czi](https://github.com/LieberInstitute/dotdotdot/blob/master/images/Human1.czi) file has the following channels

<img src="https://github.com/nikmerlock97/openRNA/blob/master/images/MAX_Human2-DAPI.png" title="DAPI" width="225"/> <img src="https://github.com/LieberInstitute/dotdotdot/blob/master/images/MAX_Human2-520.png" title="Opal 520" width="225"/> <img src="https://github.com/LieberInstitute/dotdotdot/blob/master/images/MAX_Human2-570.png" title="Opal 520" width="225"/> <img src="https://github.com/LieberInstitute/dotdotdot/blob/master/images/MAX_Human2-620.png" title="Opal 520" width="225"/> <img src="https://github.com/LieberInstitute/dotdotdot/blob/master/images/MAX_Human2-690.png" title="Opal 520" width="225"/> <img src="https://github.com/LieberInstitute/dotdotdot/blob/master/images/MAX_Human2-Lip.png" title="Opal 520" width="225"/> <br/>

The corresponding segmentions from Dotdotdot

<img src="https://github.com/LieberInstitute/dotdotdot/blob/master/output/Human2_segmentation_DAPILp3.jpg" title="DAPI" width="225"/> <img src="https://github.com/LieberInstitute/dotdotdot/blob/master/output/Human2_segmentation_Opal520_Lp20.jpg" title="Opal 520" width="225"/> <img src="https://github.com/LieberInstitute/dotdotdot/blob/master/output/Human2_segmentation_Opal570Lp1_0.jpg" title="Opal 520" width="225"/> <img src="https://github.com/LieberInstitute/dotdotdot/blob/master/output/Human2_segmentation_Opal620_Lp20.jpg" title="Opal 520" width="225"/> <img src="https://github.com/LieberInstitute/dotdotdot/blob/master/output/Human2_segmentation_Opal690Lp30.jpg" title="Opal 520" width="225"/> <img src="https://github.com/LieberInstitute/dotdotdot/blob/master/output/Human2_segmentation_No103_Lipofuscin_63x.jpg" title="Opal 520" width="225"/> <br/>

## Under Construction
* Data visualization of Image-level and ROI-level statistics
* Implementation of automated analysis of LIF (z-stack) files
* Python version of toolbox 


##

Forked from [LieberInstitute/dotdotdot](https://github.com/LieberInstitute/dotdotdot)

<!-- <h1 align="center"> openRNA </h1 -->
# openRNA

Open-source toolbox and workflows for automated analysis of RNAscope data from human and mouse

## Current Features
### Automated analysis of RNAscope data
  * Automated cell counting (currently works for TIF and CZI files only)
  
  * [Mouse](docs/mouse_vignette.md) & [Human](docs/human_vignette.md) example workflows
  
    * Same matlab [toolbox](https://github.com/nikmerlock97/openRNA/tree/master/toolbox) is used for both data sets.
  

### Image-level and ROI-level (or nuclei-level) statistics
  * Outputs 2 CSVs after automated analysis of TIF or CZI file(s)
 
    * `man.csv` represents *image-level* summary statistics for each channel of input data
   
    * `longdat.csv` represents *ROI-level* (or *nuclei-level*) summary statistics for each channel of input data

  * These two CSVs can be read into R (or python, or Matlab, or your favorite statistical sofware tool). 



## Under Construction
* Automated analysis of LIF (z-stack) files
* Python version of toolbox 


##

Forked from [LieberInstitute/dotdotdot](https://github.com/LieberInstitute/dotdotdot)

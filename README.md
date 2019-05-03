# ANTs Ecosystem Overview

Brief introductory material showcasing R and Python wrapping of ANTs functionality

# 9:15 - 10: Special Intro to ANTs (for ICERM grads and postdocs)

* background (discussed in parallel with installation)

    * [ITK](https://github.com/InsightSoftwareConsortium/ITK) and [ANTs](https://github.com/ANTsX/ANTs)
 
    * ANTs history and current development strategy ( [google scholar](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C30&q=%22Nicholas+tustison%22+or+%22Brian+avants%22&btnG=) )

    * Information resources (GitHub, Sourceforge)

* installation: see [https://github.com/stnava/ANTsRPy](https://github.com/stnava/ANTsRPy) and [https://github.com/ANTsX/ANTs/wiki/Compiling-ANTs-on-Linux-and-Mac-OS](https://github.com/ANTsX/ANTs/wiki/Compiling-ANTs-on-Linux-and-Mac-OS)

    * [ANTsR](https://github.com/ANTsX/ANTsR)

    * [ANTsPy](https://github.com/ANTsX/ANTsPy)
    
    * python docker/binder: https://github.com/stnava/ANTsPyDocker https://mybinder.org/v2/gh/stnava/ANTsPyDocker/master

    * R docker/binder: https://github.com/stnava/ANTsRDocker https://mybinder.org/v2/gh/stnava/ANTsRDocker/master

these will evolve as our tutorial material matures.

# 10:30 - 12: Intro to ANTs for Medical Imaging

* Discussion:  ITK definition of images (physical space, transformation, etc.)

* Discussion and working examples:  

    * mapping biomedical images for statistical analysis and quantification: image registration

    * labeling biomedical images for statistical analysis and quantification: image segmentation

    * template construction: toward statistical representations of image populations 

    * joint label fusion for anatomical labeling

    * functional MRI quantification - time permitting [https://github.com/stnava/structuralFunctionalJointRegistration](https://github.com/stnava/structuralFunctionalJointRegistration)

# 12 - 1:30: Lunch

# 1:30 - 3: Deep Learning and Statistical Approaches in Medical Imaging

* Discussion:  Overview of [ANTsRNet](https://github.com/ANTsX/ANTsRNet) a collection of deep learning tools for biomedical image quantification

    * Tensorflow + Keras

    * pre-trained networks

* Discussion and working examples:  

    * U-net segmentation with template-based augmentation

        * brain extraction
 
       * brain segmentation (whole image, patch-based)

       * tumor segmentation

    * Deep learning-based regression

        * super-resolution

       * Res-nets and other architectures

* Other possible topics (time permitting)

    * clustering

    * activation maps

    * deep feature maps

# 3:30 - 4:30: "Ask us about…” audience-motivated discussion of other topics

* Possible topics:

    * neuroimaging modalities:  DTI, PET, ASL, BOLD fMRI, microscopy

    * non-human primate and other animal studies

    * other organs:  lungs, heart

    * population variability:  baby brains, neurodegeneration, stroke/lesions, etc.

    * integration of imaging, genetics, psychometrics, socioeconomic status etc.

    * role of these tools in industry as applications, scientific tools in treatment of disease, etc.

# Image Object Extraction using Edge Markers Guided Watershed Transformation #

Segmentation plays an important role in computer vision and is used when we need to automate a particular activity. Computer Vision is basically divided into two parts:- object extraction and image analysis. Different techniques have been proposed to extract important features from aerial images. These techniques either use region-based techniques or edge-based methods. Unfortunately these techniques are not suitable for the high resolution images now available as they also provide us with superfluous details which are not useful for image analysis. As a consequence of this situation, two new detection techniques are used for the extraction of objects from high resolution satellite imagery. Within this framework, the project presented here focuses on edge-based region growing and edge-based watershed.

## Input Image ##

![http://lh6.ggpht.com/_IgtwgUS_nQU/TPhx1znmrzI/AAAAAAAAALI/4sGO23kqwk0/farmland1.jpg](http://lh6.ggpht.com/_IgtwgUS_nQU/TPhx1znmrzI/AAAAAAAAALI/4sGO23kqwk0/farmland1.jpg)

## Mean Shift Filtering ##

![http://lh5.ggpht.com/_IgtwgUS_nQU/TPhwHEaMYOI/AAAAAAAAAK4/IVVg9i-G1Us/colorlevel.jpg](http://lh5.ggpht.com/_IgtwgUS_nQU/TPhwHEaMYOI/AAAAAAAAAK4/IVVg9i-G1Us/colorlevel.jpg)

## Grayscale ##

![http://lh4.ggpht.com/_IgtwgUS_nQU/TPhwHSumZDI/AAAAAAAAAK8/6_mJZBCj1AY/s912/colorlevel_gray.jpg](http://lh4.ggpht.com/_IgtwgUS_nQU/TPhwHSumZDI/AAAAAAAAAK8/6_mJZBCj1AY/s912/colorlevel_gray.jpg)

## Canny Edge Detection ##

![http://lh5.ggpht.com/_IgtwgUS_nQU/TPhwHHRsNvI/AAAAAAAAAK0/PPPz1_7GkU0/s912/canny_edge.jpg](http://lh5.ggpht.com/_IgtwgUS_nQU/TPhwHHRsNvI/AAAAAAAAAK0/PPPz1_7GkU0/s912/canny_edge.jpg)

## Watershed Segmentation Using Edge Markers ##

![http://lh5.ggpht.com/_IgtwgUS_nQU/TPhwHTKv-ZI/AAAAAAAAALA/nfA751t3owA/s912/watershed.jpg](http://lh5.ggpht.com/_IgtwgUS_nQU/TPhwHTKv-ZI/AAAAAAAAALA/nfA751t3owA/s912/watershed.jpg)

## Segmented Image superimposed on the original Image ##

![http://lh4.ggpht.com/_IgtwgUS_nQU/TPhwII2vC6I/AAAAAAAAALE/s5ilkYkmwXs/s912/watershed_superimposed.jpg](http://lh4.ggpht.com/_IgtwgUS_nQU/TPhwII2vC6I/AAAAAAAAALE/s5ilkYkmwXs/s912/watershed_superimposed.jpg)
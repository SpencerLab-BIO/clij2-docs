# CLIJ 1/2/x reference in category 'binary'
This reference contains all methods currently available in CLIJ, CLIJ2 and CLIJx for processing binary images.. Read more about [CLIJs release cycle](https://clij.github.io/clij-docs/release_cycle) 

__Please note:__ CLIJ is deprecated. [Make the transition to CLIJ2](https://clij.github.io/clij2-docs/clij2_transition_notes).

<img src="images/mini_clij1_logo.png" width="18" height="18"/> Method is available in CLIJ (deprecated release)  
<img src="images/mini_clij2_logo.png" width="18" height="18"/> Method is available in CLIJ2 (stable release)  
<img src="images/mini_clijx_logo.png" width="18" height="18"/> Method is available in CLIJx (experimental release)  



__Categories:__ [Binary](https://clij.github.io/clij2-docs/reference__binary), [Filter](https://clij.github.io/clij2-docs/reference__filter), [Labels](https://clij.github.io/clij2-docs/reference__label), [Math](https://clij.github.io/clij2-docs/reference__math), [Matrices](https://clij.github.io/clij2-docs/reference__matrix), [Measurements](https://clij.github.io/clij2-docs/reference__measurement), [Neighbors](https://clij.github.io/clij2-docs/reference__neighbor), [Projections](https://clij.github.io/clij2-docs/reference__project), [Transformations](https://clij.github.io/clij2-docs/reference__transform)

<a href="#A">\[A\]</a>,<a href="#B">\[B\]</a>,<a href="#C">\[C\]</a>,<a href="#D">\[D\]</a>,<a href="#E">\[E\]</a>, F,<a href="#G">\[G\]</a>, H,<a href="#I">\[I\]</a>,<a href="#J">\[J\]</a>, K,<a href="#L">\[L\]</a>,<a href="#M">\[M\]</a>, N,<a href="#O">\[O\]</a>,<a href="#P">\[P\]</a>, Q, R,<a href="#S">\[S\]</a>,<a href="#T">\[T\]</a>, U,<a href="#V">\[V\]</a>,<a href="#W">\[W\]</a>, X, Y, Z

<a name="A"></a>

## A
### <img src="images/mini_clij1_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_automaticThreshold">automaticThreshold</a>  
The automatic thresholder utilizes the threshold methods from ImageJ on a histogram determined on  the GPU to create binary images as similar as possible to ImageJ 'Apply Threshold' method.

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_automaticThresholdInplace">automaticThresholdInplace (Experimental)</a>  
The automatic thresholder utilizes the threshold methods from ImageJ on a histogram determined on  the GPU to create binary images as similar as possible to ImageJ 'Apply Threshold' method. Enter one  of these methods in the method text field: [Default, Huang, Intermodes, IsoData, IJ_IsoData, Li, MaxEntropy, Mean, MinError, Minimum, Moments, Otsu, Percentile, RenyiEntropy, Shanbhag, Triangle, Yen]

<a name="B"></a>

## B
### <img src="images/mini_clij1_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_binaryAnd">binaryAnd</a>  
Computes a binary image (containing pixel values 0 and 1) from two images X and Y by connecting pairs of pixels x and y with the binary AND operator &. All pixel values except 0 in the input images are interpreted as 1.

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_binaryEdgeDetection">binaryEdgeDetection</a>  
Determines pixels/voxels which are on the surface of binary objects and sets only them to 1 in the  destination image. All other pixels are set to 0.

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_binaryFillHoles">binaryFillHoles</a>  
Fills holes (pixels with value 0 surrounded by pixels with value 1) in a binary image.

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_binaryIntersection">binaryIntersection</a>  
Computes a binary image (containing pixel values 0 and 1) from two images X and Y by connecting pairs of pixels x and y with the binary intersection operator &. All pixel values except 0 in the input images are interpreted as 1.

### <img src="images/mini_clij1_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_binaryNot">binaryNot</a>  
Computes a binary image (containing pixel values 0 and 1) from an image X by negating its pixel values x using the binary NOT operator !

### <img src="images/mini_clij1_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_binaryOr">binaryOr</a>  
Computes a binary image (containing pixel values 0 and 1) from two images X and Y by connecting pairs of pixels x and y with the binary OR operator |.

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_binarySubtract">binarySubtract</a>  
Subtracts one binary image from another.

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_binaryUnion">binaryUnion</a>  
Computes a binary image (containing pixel values 0 and 1) from two images X and Y by connecting pairs of pixels x and y with the binary union operator |.

### <img src="images/mini_clij1_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_binaryXOr">binaryXOr</a>  
Computes a binary image (containing pixel values 0 and 1) from two images X and Y by connecting pairs of pixels x and y with the binary operators AND &, OR | and NOT ! implementing the XOR operator.

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_boundingBox">boundingBox</a>  
Determines the bounding box of all non-zero pixels in a binary image. 

<a name="C"></a>

## C
### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_closingBox">closingBox</a>  
Apply a binary closing to the input image by calling n dilations and n erosions subsequenntly.

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_closingDiamond">closingDiamond</a>  
Apply a binary closing to the input image by calling n dilations and n erosions subsequently.

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_connectedComponentsLabeling">connectedComponentsLabeling</a>  
Performs connected components analysis to a binary image and generates a label map.

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_connectedComponentsLabelingBox">connectedComponentsLabelingBox</a>  
Performs connected components analysis inspecting the box neighborhood of every pixel to a binary image and generates a label map.

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_connectedComponentsLabelingDiamond">connectedComponentsLabelingDiamond</a>  
Performs connected components analysis inspecting the diamond neighborhood of every pixel to a binary image and generates a label map.

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_connectedComponentsLabelingInplace">connectedComponentsLabelingInplace (Experimental)</a>  
Performs connected components analysis to a binary image and generates a label map.

<a name="D"></a>

## D
### <img src="images/mini_clij1_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_dilateBox">dilateBox</a>  
Computes a binary image with pixel values 0 and 1 containing the binary dilation of a given input image.

### <img src="images/mini_clij1_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_dilateBoxSliceBySlice">dilateBoxSliceBySlice</a>  
Computes a binary image with pixel values 0 and 1 containing the binary dilation of a given input image.

### <img src="images/mini_clij1_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_dilateSphere">dilateSphere</a>  
Computes a binary image with pixel values 0 and 1 containing the binary dilation of a given input image.

### <img src="images/mini_clij1_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_dilateSphereSliceBySlice">dilateSphereSliceBySlice</a>  
Computes a binary image with pixel values 0 and 1 containing the binary dilation of a given input image.

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_distanceMap">distanceMap</a>  
Generates a distance map from a binary image. 

<a name="E"></a>

## E
### <img src="images/mini_clij1_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_erodeBox">erodeBox</a>  
Computes a binary image with pixel values 0 and 1 containing the binary erosion of a given input image. 

### <img src="images/mini_clij1_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_erodeBoxSliceBySlice">erodeBoxSliceBySlice</a>  
Computes a binary image with pixel values 0 and 1 containing the binary erosion of a given input image. 

### <img src="images/mini_clij1_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_erodeSphere">erodeSphere</a>  
Computes a binary image with pixel values 0 and 1 containing the binary erosion of a given input image. 

### <img src="images/mini_clij1_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_erodeSphereSliceBySlice">erodeSphereSliceBySlice</a>  
Computes a binary image with pixel values 0 and 1 containing the binary erosion of a given input image. 

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_empty_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_excludeLabels">excludeLabels</a>  
This operation removes labels from a labelmap and renumbers the remaining labels. 

<a name="G"></a>

## G
### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_empty_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_getBoundingBox">getBoundingBox</a>  
Determines the bounding box of all non-zero pixels in a binary image. 

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_empty_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_getJaccardIndex">getJaccardIndex</a>  
Determines the overlap of two binary images using the Jaccard index. 

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_empty_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_getSorensenDiceCoefficient">getSorensenDiceCoefficient</a>  
Determines the overlap of two binary images using the Sorensen-Dice coefficent. 

<a name="I"></a>

## I
### <img src="images/mini_clij1_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_invert">invert</a>  
Computes the negative value of all pixels in a given image. 

<a name="J"></a>

## J
### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_jaccardIndex">jaccardIndex</a>  
Determines the overlap of two binary images using the Jaccard index. 

<a name="L"></a>

## L
### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_labelSpots">labelSpots</a>  
Transforms a binary image with single pixles set to 1 to a labelled spots image. 

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_empty_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_labelVoronoiOctagon">labelVoronoiOctagon</a>  
Takes a labelled image and dilates the labels using a octagon shape until they touch. 

### <img src="images/mini_clij1_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_localThreshold">localThreshold</a>  
Computes a binary image with pixel values 0 and 1 depending on if a pixel value x in image X  was above of equal to the pixel value m in mask image M.

<a name="M"></a>

## M
### <img src="images/mini_clij1_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_mask">mask</a>  
Computes a masked image by applying a binary mask to an image. 

### <img src="images/mini_clij1_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_maskStackWithPlane">maskStackWithPlane</a>  
Computes a masked image by applying a binary 2D mask to an image stack. 

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_meanClosestSpotDistance">meanClosestSpotDistance</a>  
Determines the distance between pairs of closest spots in two binary images. 

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_meanOfMaskedPixels">meanOfMaskedPixels</a>  
Determines the mean intensity in a masked image. 

<a name="O"></a>

## O
### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_openingBox">openingBox</a>  
Apply a binary opening to the input image by calling n erosions and n dilations subsequenntly.

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_openingDiamond">openingDiamond</a>  
Apply a binary opening to the input image by calling n erosions and n dilations subsequenntly.

<a name="P"></a>

## P
### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_pullAsROI">pullAsROI</a>  
Pulls a binary image from the GPU memory and puts it on the currently active ImageJ window as region of interest.

<a name="S"></a>

## S
### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_skeletonize">skeletonize (Experimental)</a>  
Erodes a binary image until just its skeleton is left. 

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_sorensenDiceCoefficient">sorensenDiceCoefficient</a>  
Determines the overlap of two binary images using the Sorensen-Dice coefficent. 

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_empty_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_statisticsOfBackgroundAndLabelledPixels">statisticsOfBackgroundAndLabelledPixels</a>  
Determines bounding box, area (in pixels/voxels), min, max and mean intensity   of background and labelled objects in a label map and corresponding pixels in the original image.

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_statisticsOfLabelledPixels">statisticsOfLabelledPixels</a>  
Determines bounding box, area (in pixels/voxels), min, max and mean intensity   of labelled objects in a label map and corresponding pixels in the original image. 

<a name="T"></a>

## T
### <img src="images/mini_clij1_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_threshold">threshold</a>  
Computes a binary image with pixel values 0 and 1. 

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_thresholdDefault">thresholdDefault</a>  
The automatic thresholder utilizes the Default threshold method implemented in ImageJ using a histogram determined on  the GPU to create binary images as similar as possible to ImageJ 'Apply Threshold' method.

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_thresholdHuang">thresholdHuang</a>  
The automatic thresholder utilizes the Huang threshold method implemented in ImageJ using a histogram determined on  the GPU to create binary images as similar as possible to ImageJ 'Apply Threshold' method.

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_thresholdIJ_IsoData">thresholdIJ_IsoData</a>  
The automatic thresholder utilizes the IJ_IsoData threshold method implemented in ImageJ using a histogram determined on  the GPU to create binary images as similar as possible to ImageJ 'Apply Threshold' method.

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_thresholdIntermodes">thresholdIntermodes</a>  
The automatic thresholder utilizes the Intermodes threshold method implemented in ImageJ using a histogram determined on  the GPU to create binary images as similar as possible to ImageJ 'Apply Threshold' method.

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_thresholdIsoData">thresholdIsoData</a>  
The automatic thresholder utilizes the IsoData threshold method implemented in ImageJ using a histogram determined on  the GPU to create binary images as similar as possible to ImageJ 'Apply Threshold' method.

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_thresholdLi">thresholdLi</a>  
The automatic thresholder utilizes the Li threshold method implemented in ImageJ using a histogram determined on  the GPU to create binary images as similar as possible to ImageJ 'Apply Threshold' method.

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_thresholdMaxEntropy">thresholdMaxEntropy</a>  
The automatic thresholder utilizes the MaxEntropy threshold method implemented in ImageJ using a histogram determined on  the GPU to create binary images as similar as possible to ImageJ 'Apply Threshold' method.

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_thresholdMean">thresholdMean</a>  
The automatic thresholder utilizes the Mean threshold method implemented in ImageJ using a histogram determined on  the GPU to create binary images as similar as possible to ImageJ 'Apply Threshold' method.

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_thresholdMinError">thresholdMinError</a>  
The automatic thresholder utilizes the MinError threshold method implemented in ImageJ using a histogram determined on  the GPU to create binary images as similar as possible to ImageJ 'Apply Threshold' method.

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_thresholdMinimum">thresholdMinimum</a>  
The automatic thresholder utilizes the Minimum threshold method implemented in ImageJ using a histogram determined on  the GPU to create binary images as similar as possible to ImageJ 'Apply Threshold' method.

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_thresholdMoments">thresholdMoments</a>  
The automatic thresholder utilizes the Moments threshold method implemented in ImageJ using a histogram determined on  the GPU to create binary images as similar as possible to ImageJ 'Apply Threshold' method.

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_thresholdOtsu">thresholdOtsu</a>  
The automatic thresholder utilizes the Otsu threshold method implemented in ImageJ using a histogram determined on  the GPU to create binary images as similar as possible to ImageJ 'Apply Threshold' method.

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_thresholdPercentile">thresholdPercentile</a>  
The automatic thresholder utilizes the Percentile threshold method implemented in ImageJ using a histogram determined on  the GPU to create binary images as similar as possible to ImageJ 'Apply Threshold' method.

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_thresholdRenyiEntropy">thresholdRenyiEntropy</a>  
The automatic thresholder utilizes the RenyiEntropy threshold method implemented in ImageJ using a histogram determined on  the GPU to create binary images as similar as possible to ImageJ 'Apply Threshold' method.

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_thresholdShanbhag">thresholdShanbhag</a>  
The automatic thresholder utilizes the Shanbhag threshold method implemented in ImageJ using a histogram determined on  the GPU to create binary images as similar as possible to ImageJ 'Apply Threshold' method.

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_thresholdTriangle">thresholdTriangle</a>  
The automatic thresholder utilizes the Triangle threshold method implemented in ImageJ using a histogram determined on  the GPU to create binary images as similar as possible to ImageJ 'Apply Threshold' method.

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_thresholdYen">thresholdYen</a>  
The automatic thresholder utilizes the Yen threshold method implemented in ImageJ using a histogram determined on  the GPU to create binary images as similar as possible to ImageJ 'Apply Threshold' method.

<a name="V"></a>

## V
### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_varianceOfMaskedPixels">varianceOfMaskedPixels</a>  
Determines the variance in an image, but only in pixels which have non-zero values in another binary mask image. 

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_empty_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_voronoiLabeling">voronoiLabeling</a>  
Takes a binary image, labels connected components and dilates the regions using a octagon shape until they touch. 

### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_voronoiOctagon">voronoiOctagon</a>  
Takes a binary image and dilates the regions using a octagon shape until they touch. 

<a name="W"></a>

## W
### <img src="images/mini_empty_logo.png" width="18" height="18"/><img src="images/mini_clij2_logo.png" width="18" height="18"/><img src="images/mini_clijx_logo.png" width="18" height="18"/><a href="https://clij.github.io/clij2-docs/reference_watershed">watershed</a>  
Apply a binary watershed to a binary image and introduces black pixels between objects.

## Digital Image


A representation of a two-dimensional image as a finite set of digital values, called picture elements or pixels. f(x, y)

Where x, y are spatial coordinates  
$f(x, y) = i(x,y) * r(x,y)$  

$f(x, y)$: Intensity at given point (x, y)  
$i(x, y)$: Illumination at (x, y)  
$r(x, y)$: Reflectance/ Transmissivity at (x, y)

$M \times N$ representation of f

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_acccd51577d24bf78748e92dacf30e03.png)

### Image Acquisition Process






![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_7a88192c354945ab89ce216bf650662b.png)







### Pixel & Digitization

Pixels are the elements of a digital image that typically represent gray levels, colours, heights, opacities.

Digitization implies that a digital image is an approximation of a real scene in the numerical matrices form




| ![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_872518ea9e5b4e3dbb174941acfb39ba.png) | ![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_7b0e330578a040779fbe6f1594110b01.png) |
| --- | --- |


### Digital Image

Common digital image formats include
* 1 sample per point (B&W/Grayscale)
* 3 samples per point ( Red, Green, and Blue)
* 4 samples per point (Red, Green, Blue, and Alpha/opacity)

## What is Digital Image Processing?

### Digital Image Processing

Processing digital images by means of a computer.

An image processing operation typically defines a new image g in terms of an existing image f.

We can transform either the range of f. 

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_6c7c611794334508b32604240b1de84a.png)

Or the domain of f:

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_e37580ca0ff3437189f49d3f6a30aa0e.png)

### Why Digital Image Processing?

* Improvement of pictorial information for human interpretation
* Processing of image data for storage, transmission and representation for autonomous machine perception

Where image processing ends, fields such as image analysis and computer vision start. The continuum from image processing to computer vision is broken down into: 

* Low – Level:  
Inputs and outputs are images. Ex: Noise Removal, Image Sharpening
* Mid – Level:  
Outputs are the attributes extracted from input images. Ex: Object Recognition, Image Segmentation
* High – Level:  
An ensemble of recognition of individual objects. Ex: Scene Understanding, Autonomous Navigation

For more details about each step, refer to this article: https://medium.com/futframe-ai/fundamental-steps-of-digital-image-processing-d7518d6bb23c.

### Key Stages in Digital Image Processing








![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_1789b4ee9aab4cd2a7daf7f63c41d823.png)







### Applications
* Document Handling
* Signature Verification
* Biometric Verification
* Object Recognition Research
* Target Recognition
* Interpretation of aerial photography
* Autonomous Vehicle
* Traffic Monitoring
* Face Recognition and Tracking
* Medical Applications -> Tumor detection
* Image generations
* Image styling


### Notebook on Digital Image Processing

The Notebook on Digital Image Processing can be found [here](https://dphi.tech/notebooks/847/gunnika/digital-image-processing).
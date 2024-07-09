---
marp: true
theme: uncover
size: 16:9  
class: invert
backgroundColor: #151515
color: #898989
---

# Machine Vision

Is it a science or an art?  
<br>
## ?  

---  

## Contrast and Resolution  

---  

## What is contrast?

Contrast describes the separation in intensity between blacks and whites  

---  

## What is Resolution  

Resolution is a measurement of a systems ability to produce object detail  

---  

## Describe Contrast  

Contrast depends on the frequency of changes and intensity between line pairs of black and white

---

## Describe Resolution  

The measure or size of the smallest object that can be detected by the vision system   

---  
## How is Contrast Measured?

Contrast is measured by determining the distace between black and white

---  

## How is Resolution Measured?

Resolution is typically quantified in pixels per unit distance (e.g., pixels per millimeter)   

---  

## Resolution and Contrast Work Together   

Resoltion and conrast are closely linked and that connection is described by MTF  

---  

## Modulation Transfer Function (MTF)  
  
MTF is the lenses ability to reproduce contrast at a specific resolution and describes the overall performance of a system

---  

## What is a pixel?

A pixel (picture-element) is the smalled unit or part of an image or display  

---  

## Pixel Resolution  

Pixel resolution is the physical size of an image or represented by the area in pixels in width x height  

---  

## Pixel Size  

Pixel size is usually measured in micrometers (width x height) and impacts light gathering ability  

---  

## Imager Sensor Size  

Imager sensor size is directly related to pixel size and contains a specific amount of pixels

---  

## Image Quality  

The correct resolution for the application with the best possible contrast discerning features  

---  

## Resolution and Contrast Summary  

Resolution and contrast are determined by sensor size in pixels and quality of optics to produce an ideal MTF with available contrast  

---  

## Imaging Devices and Components  

Names and descriptions of system devices and componenets  

---  

## Camera  

A camera is a physical device that houses imaging components and mounting hardware that convert captured energy into numeric representation   

---  

## Lens  

A lens determines what the camera "sees" in the real world, provides maginification of a scene,and focuses the collected light onto a sensor

---  

## Sensor  

A sensor converts focused light from the lens into electrical signals for processing  

---  

## Filter  

A filter is a device placed in front of the lens to enhance image quality, improve contrast, reduce glare, and isolate specific wavelengths of light to emphasize certain features of the object being imaged.  

---  

## Application Software  

Aplication software is tightly linked to the hardware components and varies with real-world applications  

---  

## Field of View  

Field of view is the obserable area by system measured in millimeters (width x height)<br>  
The viewable area of and around the object of inspection  

---  

## Angular Field of View  

The angular extent of the observable scene that a camera can capture, measured in degrees.

---  

## Working Distance  

Working distance is the distance between the front of the camera lens and the object being imaged; determined by angular field of view  

---  

## Focal Length  

Focal Length is the distance between the lens's center and the image sensor usually measured in millimeters  

---  

## PMAG (Primary magnification)  

PMAG is the degree if magnification and angular field of view stated in millimeters  

---  

## PMAG Usage  

Microscopes and telecentric lenses are always described with PMAG  

---  

## Exposure  

Exposure is the controlled amount of light let into a sensor over a period of time  

---  

## Entocentric Lenses  

Entocentric (endocentric) lenses have perspective with wide angles and shorter working distances with less distortion (fixed focal length; prime)  

---  

## Telecentric Lenses  

Telecentric lenses have a perpendicular view with almost no angle or perspective

---  

## Collimated Light  

Collimated light are rays of light (particles) that are made to be accurately parallel

---  

## Angle of Incidence  

Angle of incidence is the angle that light rays contact a surface relative to the normal perpendicular point  

---  

## Lens Resolution  

Lens resolution is what size pixel can the lens resolve  

---  

## Use a lens calculator  

Use a lens calculator to get close and check your work  

---  

## Spatial Resolution  

The ability of an imaging system to distinguish between objects or details that are close together  

---  

## Image Resolution  

Image resolution is the number of pixels in an image, usually expressed as width × height<br> (e.g., 1920×1080 pixels)  

---  

## Pixel Spatial Resololution  

Pixel spatial resolution is the number of pixels within a specific area of a sensor, sometimes expressed in pixels per inch (PPI) or PPM<br>  

---  

## Pixel Spatial Resolution Cont.  

FOV / Image Resolution<br>  
height or width / height or width  

---  

## Line Pairs Per Millimeter  

Line pairs per millimeter determine the image space resolution in "frequency" (how often) of contrasting pixels  

---  

## Spatial Frequency  

Spatial prequency includes cycles per millimeter and pixel size  

---  

## Spatial Resolution Consideration  

Spatial resolution takes the average of the two dimensions if they are drastically different  

---  

## Imaging Angle **IS** Perspective  

Imaging angle is the angle formed between the lens and the surface it is pointed at  

---  

## Pixel Size Calculation  

10 micron = 50 line pairs per millimeter<br>  
5 micron = 100 line pairs per millimeter<br>  
Pixel size = 500 / frequency  

---  

## Good MTF is Unique  

*Good* MTF is application specific and dependant  

---  

## What Affects MTF?  

- abberations  
- working distance  
- wave length  
- F# (f-stop)  

---  

## Aberration  

Abberation is deviation from the expected or ideal image due to imperfections in the **system**  

---  

## Working Distance  

Working distance is the distance from the front of the lens to the object  

---  

## Wavelength  

The portion of the electromagnetic spectrum that is visible to the image system  

---  

## F# (f-stop)  

F# (f-stop) is the ratio of the focal length to the diameter of the lens opening  

---  

## Diffraction Limit  

Diffraction limit is the line of perfect lens performance  

---  

## Relative Illumination  

Relative illumination is the brightness of a lens fromt the center to a corner relative to the brightest spot in the image  

---  

## Smaller Pixels = Higher Resolution  

More smaller pixels fit into a space then larger pixels  

---  

## Limiting Contrast for Machines  

Limiting contrast for machines is 10% - 20%  

---  

## Create Contrast  

When you want to create contrast, think of the color that is not the color you want to contrast  

---  

##  How Do Image systems see light?  

Image systems, cameras and sensors, all capture light in photons at a wavelength  

---  

## Visible Light Sprectrum  

400nm - 750nm<br>  
(380nm-740nm)  

---  

## Optical Spectrum for Machines  

300nm - 3000nm  

---  

## Near-Infrared  

700nm - 1000nm  

---  

## What is light?  

Light is electro-magnetic (EM) energy of transverse waves and photons  

---  

## Grayscale  

Basic image format<br>  
255 = pure white and 0 = black<br>  
### **0 = no data**  

---  

## 254 > 255  

254 is better than 255 (pure white) because 255 could "wash out" or "cover up" missing necessary data  

---  

## Filters in Machine Vision  

Filters in machine vision  are optical components, usually lens covers that selectively transmit or block specific wavelengths, spectrums, or ranges of wavelengths of light

---  

## Bayer Filter  

 A color filter array for arranging RGB color filters on a square grid of photosensors  

 ---  

 ## What do Bayer Filters do?

 Bayer filters sample single colors from each pixel, deriving color values from neighboring pixels  

 ---  

 ## Bayer Filters Will Reduce Resolution  

 Bayer filters will reduce resolution because neighboring pixels are processed and combined  

 ---  

 ## A Filter's Color  

 A filter's color lets that *color* pass through to the lens and it appears lighter in contrast to non-filtered *colors*  

 ---  

 ## Color Filter Example  

 Red light with a red bandpass filter removes all of the other wavelengths (colors) a the *red* color appears brigther in contrast  

 ---  

## Bayer Filtering is Most Popular  

Bayer filtering is the most popular because of it's use processed into RGB  

---  

## What is Opaque?  

Opaque is a material's ability to block light<br>  
No object is technically opaque, but *maybe* opaque to a particular spectrum  

---  

## The Color Wheel  

Insert an image of a color wheel  
*Red and Green* are compliments<br>  
*Orange and Blue* are compliments<br>  
*Yellow and Violet* are compliments  

---  

## Image Quailty Key Points  

- resolution  
- contrast  
- depth of field  
- perspective  
- distortion  

---  

## Resolution  

Resuloution is the minumum feature size of the object  

---  

## Contrast  

Contrast is the difference in brightness that makes an object distinguishable from other objects *and* the background.

---  

## Depth of Field  

Depth of Field is the maximum object depth that can be maintained entirely in focus  

---  

## Perspective  

Perspective refers to the way objects appear smaller as they get further from the viewer, creating a sense of depth and spatial relationships in a two-dimensional image, influenced by the focal length of the lens and the position of the cameras.  

---  

## Distortion  

Distortion refers to the deviation from the rectilinear projection, causing straight lines to appear curved or otherwise altered, resulting in a misrepresentation of the true shape of objects within the image.

---  

## Sensor Selection  

The size of the sensor and the sensor format are critical to sensor selection  

---  

##  Sensor Size  

The size of the camera sensor's active area specified in fractions of an inch  

---  

## Sensor Technologies  

Different sensor technologies require different wavelengths  

---  

## Light Energy  

Light energy is a form of electromagnetic energy that travels in waves. And is essential for illuminating objects so that they can be imaged by a camera sensor  

---  

## Correct Lighting  

Correct lighting must be repeatable relative to a background and overcome object variations  

---  

## Illumination "W"  

Insert an image of an illumination "W"<br>  
Light that reflects in a "W" and "V" pattern from the source into the camera<br>  
light will nly deliver it's specular reflection back to the camera  

---  

## Relative Illumination  

Relative illumination in optical systems and machine vision describes how the intensity of light varies across the image sensor

---  

## Relative Ilumintation Cont.  
- compact lenses have better relative illumination  
- Higher resolution lenes have better relative illumination  

---  

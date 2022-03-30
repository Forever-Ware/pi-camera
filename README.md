# Rasberry Pi - Camera V2 

# Simple Demo project to scan qr codes from video and Images

**Development **
- Use raspberry buster full os since it has python 3.7 due to numpy issue
- https://packages.debian.org/buster/python3
- https://downloads.raspberrypi.org/raspbian/images/raspbian-2020-02-14/
- Legacy --> https://www.raspberrypi.com/software/operating-systems/#raspberry-pi-os-legacy


**Overview: **
- Runs on port: localhost://8080 

**Features:** 
-  Analysis video to determine the QR Code
-  Take single image shots 
  - Slice image into sections depending on number of containters 
  - Determine qr data of sectional image from full image 

**Libaries**
OpenCV 
Numpy
ImageAi


**Todo: ML using tensor flow **

PI4 end: Use cloud vision api to get json response of sent image. 

Cloud End: push image to collection `` document `` to trigger on update cloud function cloud vision api getting json response of image

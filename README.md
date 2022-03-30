# Rasberry Pi - Camera V2 

# Simple Demo project to scan qr codes from video and or images

# Development use raspberry buster full os since it has python 3.7 due to numpy issue


**Overview: **
- Runs on port: localhost://8080 

**Features:** 
-  Analysis video to determine the QR Code
-  Take single image shots 
  - Slice image into sections depending on number of containters 
  - Determine qr data of sectional image from full image 
- 

**Libaries**
Use OpenCV and Numpy to complete this project 

**#Todo: ML using tensor flow **
Use cloud vision api to get json response of sent image. 
Cloud End: push image to collection `` document `` to trigger on update cloud function cloud vision api getting json response of image

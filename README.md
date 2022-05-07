
# PCB Defect Detection Using Image Processing

This project aims to detect and classify defects in PCBs using image processing techniques.



## Used Images
![image](https://user-images.githubusercontent.com/80588457/167242322-0eedf9a4-ab4d-4354-aa7c-4c7138bb0192.png)

## Image Pre-Processing
Used multiple Image Pre-Processing Techniques to clean the images and reducing noises

Gray-Scaling

Median Filtering

Gausian Filtering

## Image Histogram
Image Histogram shows three bumps based on gray scale level ( Background < Wiring < Soldering )
![image](https://user-images.githubusercontent.com/80588457/167242930-48886607-452b-4e68-8349-f9eba5be01c7.png)


## Image Segmantation

Used Multi-level thresholding to sagment the images in three parts ( Background < Wiring < Soldering )

![image](https://user-images.githubusercontent.com/80588457/167242914-83c03df4-1bcd-46ee-9ac7-a02476dacb17.png)

## Defects
Classified defetcs as positive and nagative defects.

![image](https://user-images.githubusercontent.com/80588457/167242613-dec2fb09-b215-4d35-9a2c-831020f9e71c.png)


## Result

Nagateive defects shown as red color and Positive defects are shown as blue color
![image](https://user-images.githubusercontent.com/80588457/167242949-8994ca2d-b3ce-4f22-bfae-d4626ac6e59f.png)




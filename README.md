# Histogram-of-an-images
## Aim
To obtain a histogram for finding the frequency of pixels in an Image with pixel values ranging from 0 to 255. Also write the code using OpenCV to perform histogram equalization.

## Software Required:
Anaconda - Python 3.7

## Algorithm:
### Step1:
Read the gray and color image using imread()

### Step2:
Print the image using imshow().

### Step3:
Use calcHist() function to mark the image in graph frequency for gray and color image.

### step4:
Use calcHist() function to mark the image in graph frequency for gray and color image.

### Step5:
The Histogram of gray scale image and color image is shown.


## Program:
### Developed By: NARAMALA KUMARTEJA
### Register Number: 212223230132
### Input Grayscale Image and Color Image
## Gray Image:
```
import cv2
import matplotlib.pyplot as plt
image = cv2.imread('Prabhas.jpeg')
gray_image = cv2.cvtColor(image, cv2.COLOR_BGR2GRAY)
plt.imshow(gray_image, cmap='gray')
plt.title('Original Grayscale Image')
plt.axis('on')
```
![image](https://github.com/user-attachments/assets/82ef158b-a20a-461e-a739-c1aaca2b5cfb)

## Color Image:
```
color_image=cv2.imread('Prabhas.jpeg')
plt.imshow(color_image)
plt.axis('on')
plt.show()
```
![image](https://github.com/user-attachments/assets/288d71a4-4f71-4632-961b-a14df19487f6)
### Histogram of Grayscale Image and any channel of Color Image
## Gray Image:

## Color Image:

### Histogram Equalization of Grayscale Image.

## Result: 
Thus the histogram for finding the frequency of pixels in an image with pixel values ranging from 0 to 255 is obtained. Also,histogram equalization is done for the gray scale image using OpenCV.

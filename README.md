# DIP-Workshop-01
```
Name: Nathin R
Reg.No.:212222230090
```
## Orginal Image
```
import cv2
image=cv2.imread('nathin.jpg',1)
image=cv2.resize(image,(500,350))
cv2.imshow('Nathin',image)
cv2.waitKey(0)
cv2.destroyAllWindows()
```
![image](https://github.com/NathinR/DIP-Workshop-01/assets/118679646/d414e2ae-bae5-47b0-bb76-9565e6f5f9cf)

## Gray Scale and HSV image
```
import cv2
img = cv2.imread('nathin.jpg',1)
img = cv2.resize(img,(300,200))
cv2.imshow('Original Image',img)

hsv1 = cv2.cvtColor(img,cv2.COLOR_BGR2HSV)
cv2.imshow('BGR2HSV',hsv1)

hsv2 = cv2.cvtColor(img,cv2.COLOR_RGB2HSV)
cv2.imshow('RGB2HSV',hsv2)

gray1 = cv2.cvtColor(img,cv2.COLOR_BGR2GRAY)
cv2.imshow('BGR2GRAY',gray1)

gray2 = cv2.cvtColor(img,cv2.COLOR_RGB2GRAY)
cv2.imshow('RGB2GRAY',gray2)

cv2.waitKey(0)
cv2.destroyAllWindows()
```
![image](https://github.com/NathinR/DIP-Workshop-01/assets/118679646/2b8845df-4863-4304-82a2-e412084ec58c)

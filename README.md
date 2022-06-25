# working-on-image
## program:
```python

# Developed By:Loghul M
# Register Number:212220230029

import cv2
import matplotlib.pyplot as plt
img=cv2.imread("loghulm.jpg",1)
img=cv2.resize(img,(400,300))
plt.title('Flower(original image)')
plt.imshow(img)


# gray image
gray = cv2.cvtColor(img,cv2.COLOR_BGR2GRAY)
plt.title('Gray Image')
plt.imshow(gray)


# hsv image
hsv = cv2.cvtColor(img,cv2.COLOR_BGR2HSV)
plt.title("Hsv Image")
plt.imshow(hsv)
h,s,v=cv2.split(hsv)

# h plane
plt.title('H plane')
plt.imshow(h)

# s plane
plt.title('S plane')
plt.imshow(s)

# v plane
plt.title('V plane')
plt.imshow(v)
```
## <br/> <br/> <br/> <br/> <br/>Output
![s1](https://user-images.githubusercontent.com/78194419/175784190-f73506c6-6c19-4208-a1ea-4d802d6188f1.jpg)
![s2](https://user-images.githubusercontent.com/78194419/175784189-dbd22c07-ac3c-4e24-a51d-e110fc8f4e80.jpg)
![s3](https://user-images.githubusercontent.com/78194419/175784187-e69f638c-e574-4de0-a835-8057cdf07bfb.jpg)


![s4](https://user-images.githubusercontent.com/78194419/175784193-62568e96-7c00-4f4d-ae7e-02ecaaa480d2.jpg)
![s5](https://user-images.githubusercontent.com/78194419/175784192-76d82fc8-12b2-4efe-9792-92a167ea8b99.jpg)
![s6](https://user-images.githubusercontent.com/78194419/175784191-2a592ad2-5dc5-4815-9a7e-5af9cfabc016.jpg)

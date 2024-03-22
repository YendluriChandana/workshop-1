### DIPT-WORKSHOP-1
# NAME: YENDLURI CHANDANA
# REG NO: 212223100063
# DESCRIPTION
1.Take any one of the image like plant,Tree,Flower or building.
2.Read the image and write the image with your name as filename(eg,elsa.jpg).
3.Convert the file name into Gray Scale image and HSV image.
4.Display the H,S and V planes.
## PROGRAM:
```
import cv2
image=cv2.imread('flower.jpg')
cv2.imshow('CHANDANA',image)
cv2.waitKey(0)
cv2.destroyAllWindows()

#converting color image into gray image
gray = cv2.cvtColor(image,cv2.COLOR_BGR2GRAY)
cv2.imshow('GRAY',gray)
cv2.waitKey(0)
cv2.destroyAllWindows()


#converting color image into HSV image
hsv = cv2.cvtColor(image,cv2.COLOR_BGR2HSV)
cv2.imshow('HSV',hsv)
cv2.waitKey(0)
cv2.destroyAllWindows()

#splitting H,S,V planes
H,S,V=cv2.split(image)
cv2.imshow('Hue',H)
cv2.imshow('Saturation',S)
cv2.imshow('Value',V)
cv2.waitKey(0)
cv2.destroyAllWindows()
```
### OUTPUT
## Original image
![image](https://github.com/YendluriChandana/workshop-1/assets/139842204/b015f4c5-ae45-4759-9d09-9a8f41383d40)
## Converting Colour image into HSV
![image](https://github.com/YendluriChandana/workshop-1/assets/139842204/18ae87e5-bbbe-4b61-98b9-44f574579fcd)
## Converting Colour image into gray image
![image](https://github.com/YendluriChandana/workshop-1/assets/139842204/208292c6-3ff6-4437-8dbb-45db26aa3a40)
## Splitting the image into H,S,V Planes:
![Screenshot 2024-03-22 082940](https://github.com/YendluriChandana/workshop-1/assets/139842204/eddb62f9-c14e-4bc8-9032-350562c559f4)
## RESULT:
Therefore the picture is converted into Gray,HSV image and split into H,S,V planes successfully using python.







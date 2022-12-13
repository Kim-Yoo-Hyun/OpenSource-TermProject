# OpenSource-TermProject

## Key points
-------
### 1. Problem understanding
1)	Find image named family
2)	Define blurred to use 
3)	Capture ‘face’ from picture
4)	Make ‘face’ blurred by using blurred which we defined 
--------
### 2. Problem Solving 
1)	Using ‘cv2.imread’ to read ‘family.png’
2)	Define blurred using ‘cv2.blur(img, (50, 50))
3)	Detect ‘face’ by using Cascade and read ‘family.png’ 
4)	Detect ‘face’ by using Cascade and blurred which we defined
--------
### 3.	Methods
1)	cv2.imread(), cv2.waitkey(), cv2.destroyAllWindows() 
2)	cv2.CascadeClassifier: It is a progress of stepping to exclude which is not a face by using features of darkness.  
3)	cv2.Cascade.detectMultiScale: Read and detect the object by using the data which was stored before. 
4)	Haarcascade_frontalface_default.xml: Detect the face of front
---------
### 4.	Limitation
1)	It can’t detect face if it is hided 
---------
### 5.	Reference 
-	https://blog.naver.com/playonu/222702485973
-	https://github.com/opencv/opencv/tree/master/data/haarcascades

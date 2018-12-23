# raspberryPi_Yolo
## 개요 
Yolo를 이용한 PeopleCounting

## 1. 사전준비

#### 1) [라즈베리파이 준비](https://github.com/diqmwl/raspberryPi_OS_Install)

#### 2) [OpenCV 설치](http://blog.xcoda.net/97)
버전은 3.3.0으로 설치했고 링크를 참고 했습니다.

#### 3) Yolo설치 (OpenCV가 설치된 폴더에서 진행합니다)
1. apt update

	```
	[ubuntu ~]$ sudo apt update
	```

2. yolo download

	```
	[ubuntu ~]$ git clone https://github.com/AlexeyAB/darknet
	```
	
	```
	[ubuntu ~]$ cd darknet
	```
저는 라즈베리파이에서는 AlexeyAB버전을 사용해야 오류가 나지않아서 사용했습니다.

3. Makefile 수정

	```
	[ubuntu ~]$ sudo nano Makefile
	```

테스트용 이미지(img_test.png)와 분할 및 병합한 이미지 그리고<\n> 
이미지 분할용 코드와<\n> 
이미지 변환 및 병합 코드<\n> 
모두 한 디렉토리에 올려져 있고 같은 디렉토리에서 동작하도록 했습니다.</br>

코드 실행 방법은 다음과 같습니다.</br></br></br>



### 1. 이미지 분할
예시)

```python cut_image_mn_function.py --imgfile=test_img.png --cols=3 --rows=4 --prefix=test```</br></br>




### 2. 이미지 변환 및 병합
-> filenameprefix에 이미지 분할했던 mxn의 크기를 같이 입력해야 다.

예시)

```python merge_image_function.py --filenameprefix=test_3X4 --cols=3 --rows=4 --outputname=merged```

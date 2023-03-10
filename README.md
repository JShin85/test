이미지 분할용 코드는 cut_image_mn_function.py 이며 
이미지 변환 및 병합 코드는 merge_image_function.py 입니다.

코드 실행 방법은 다음과 같습니다.</br></br></br>



### 1. 이미지 분할
예시)

```python cut_image_mn_function.py --imgfile=test_img.png --cols=3 --rows=4 --prefix=test```</br></br>




### 2. 이미지 변환 및 병합
-> filenameprefix에 이미지 분할했던 m*n의 크기를 입력해야 이미지 로드가 됩니다.

예시)

```python merge_image_function.py --filenameprefix=test_3X4 --cols=3 --rows=4 --outputname=merged```

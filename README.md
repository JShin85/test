코드 실행 방법은 다음과 같습니다.

# 이미지 분할
예시)
python cut_image_mn_function.py --imgfile=test_img.png --cols=3 --rows=4 --prefix=test


# 이미지 변환 및 병합
권장: filenameprefix는 분할 하고 싶은 m*n의 크기를 함께 입력

예시)
python merge_image_function.py --filenameprefix=test_3X4 --cols=3 --rows=4 --outputname=merged

# 11월 환경셋팅

1. OpenCV 설치에서 더 진행 못하는 문제
https://blog.naver.com/roboholic84/221629374217

2. Jupiter Notebook에서 코드 입력시 CV인지 못함

import cv2

img_source = "hillary.jpg"

img = cv2.imread(img_source)

cv2.imshow('OMG',img)
cv2.waitKey()
cv2.destroyAllWindows()
---------------------------------------------------------------------------
ModuleNotFoundError                       Traceback (most recent call last)
<ipython-input-1-f3bfbcf87852> in <module>
----> 1 import cv2
      2 
      3 img_source = "hillary.jpg"
      4 
      5 img = cv2.imread(img_source)

ModuleNotFoundError: No module named 'cv2'

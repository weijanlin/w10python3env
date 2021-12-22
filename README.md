# 在Windows 10 的環境下如何準備好Python3 的AI環境

## 安裝Python3
要注意要勾 Path 

## 安裝OpenCV2 
因為只有裝Python 3沒有裝Python 2 所以預設的Python 就是Python3 了.
```
python -m pip install --upgrade pip
python -m pip install opencv-python
```
實測一下OpenCV2 版本
```
python
import cv2
cv2.__version__
```
結果會出現版本例如：
```
4.5.4
```

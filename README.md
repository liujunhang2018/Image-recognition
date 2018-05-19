# python 图片识别  

通过python来识别图片中的字，代码极短，但是却需要下载几个库

## 环境  
python3 乌班图16.04 

## 库文件的下载  
### 安装PIL 
在Debian/Ubuntu Linux下直接通过apt安装：

$ sudo apt-get install python-imaging

Mac和其他版本的Linux可以直接使用easy_install或pip安装，安装前需要把编译环境装好：

$ sudo easy_install PIL

如果安装失败，根据提示先把缺失的包（比如openjpeg）装上。
Windows平台就去PIL官方网站下载exe安装包。

### 安装pytesseract  

 sudo pip3 install pytesseract  
 
### 安装tesseract-ocr识别引擎 

安装tesseract-orc前必要的依赖：

sudo apt-get install libpng12-dev  
sudo apt-get install libjpeg62-dev  
sudo apt-get install libtiff4-dev  
sudo apt-get install gcc  
sudo apt-get install g++  
sudo apt-get install automake  


安装tesseract-ocr 

sudo apt-get install tesseract-ocr  

安装语言文件（英文、中文简体）

sudo apt-get install tesseract-ocr-eng  
sudo apt-get install tesseract-ocr-chi-sim 

如果需要什么文件，可以去官网下载 。
https://code.google.com/p/tesseract-ocr/downloads/list

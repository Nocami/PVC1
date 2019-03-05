# PythonComputerVision-1  
## 说明：  
此项目为“python计算机视觉”的新手学习历程，时间跨度大约半年左右，本文为第一集，相关系列文章会随时更新，敬请期待。  
## 注意：  
此项目所有代码均运行与Python 2.7.10版本，所需库文件需自行下载，这里推荐直接安装python(x,y)，其中不仅包括了python本身，还附带有所需的所有库文件以及编译器。下载链接：  
https://www.softpedia.com/get/Programming/Other-Programming-Files/Python-x-y.shtml  
![image](https://github.com/Nocami/PythonComputerVision-1/blob/master/image/%E6%8D%95%E8%8E%B7.JPG)


## python图像处理基础  
### PIL-Python图像库  
PIL (Python Imaging Library)图像库提供了很多常用的图像处理及很多有用的图像基本操作。PIL库下载地址[www.pythonware.com/products/pil/] 。  
灰度图是一切处理的基础，下面演示读入一幅图片以及将其二值化（转化为灰度图）的例子：  
运行代码 1.1.py，即可得到如下图所示：  
![image](https://github.com/Nocami/PythonComputerVision-1/blob/master/image/%E5%8E%9F%E5%9B%BE%E7%81%B0%E5%BA%A6%E5%9B%BE.jpg)  
### 图像轮廓和直方图  
图像轮廓线和图线等高线。在画图像轮廓前需要转换为灰度图像，因为轮廓需要获取每个坐标[x,y]位置的像素值。  
运行 1.2.2图像轮廓和直方图.py 即可得到如下图所示例子：  
![image](https://github.com/Nocami/PythonComputerVision-1/blob/master/image/%E5%9B%BE%E5%83%8F%E8%BD%AE%E5%BB%93%E5%92%8C%E7%9B%B4%E6%96%B9%E5%9B%BE.jpg)    
### 高斯滤波（高斯模糊、图像差分）  
一个经典的并且十分有用的图像卷积例子是对图像进行高斯模糊。高斯模糊可以用于定义图像尺度、计算兴趣点以及很多其他的应用场合。  
运行库中附带的 1.4.1高斯模糊.py ，即可得到对图像进行模糊显示的效果：  
![image](https://github.com/Nocami/PythonComputerVision-1/blob/master/image/%E9%AB%98%E6%96%AF%E6%A8%A1%E7%B3%8A.jpg)  
上面第一幅图为待模糊图像，第二幅用高斯标准差为2进行模糊，第三幅用高斯标准差为5进行模糊，最后一幅用高斯标准差为10进行模糊。关于该模块的使用以及参数选择的更多细节，可以参阅SciPy scipy.ndimage文档[docs.scipy.org/doc/scipy/reference/ndimage.html] 。  
运行库中附带的 1.4.2高斯图像差分.py ，即可得到对图像差分显示的效果：  
![image](https://github.com/Nocami/PythonComputerVision-1/blob/master/image/%E5%9B%BE%E5%83%8F%E5%B7%AE%E5%88%86.jpg)    
上面代码中，第一行标准差为2，列分别表示的是x、y和mag,第二行和第三行依次类推。   
### 直方图均衡化  
图像均衡化作为预处理操作，在归一化图像强度时是一个很好的方式，并且通过直方图均衡化可以增加图像对比度。  
下面是运行库中文件 1.3.3直方图均衡化.py 所显示的关于图片直方图均衡化的示例：  
![image](https://github.com/Nocami/PythonComputerVision-1/blob/master/image/%E7%9B%B4%E6%96%B9%E5%9B%BE%E5%9D%87%E8%A1%A1%E5%8C%96.jpg)   
  
 ## 总结  
 上述内容为python图像处理的基础部分，简单介绍了一些术语的概念，并且附上了py文件源码以及相应的效果演示示例。  
 ps：图片为nocami本人，对图片保留肖像权，请勿作他用。    
 # ----------------------------------------------------------------------------------------------------------------------------------  
 # ----------------------------------------------------------------------------------------------------------------------------------
  
# EnglishEdition
# PythonComputerVision-1
## Description:
This project is a newcomer learning course of "Python Computer Vision". The time span is about half a year. This article is the first episode. The related series of articles will be updated at any time, so stay tuned.
## Note:
All the code of this project is running with Python version 2.7.10. The required library files need to be downloaded by yourself. It is recommended to install python (x, y) directly, which includes not only python itself, but also all the required library files and compilation. Device. Download link:
https://www.softpedia.com/get/Programming/Other-Programming-Files/Python-x-y.shtml
![image](https://github.com/Nocami/PythonComputerVision-1/blob/master/image/%E6%8D%95%E8%8E%B7.JPG)


## python image processing basics
### PIL-Python Image Library
The PIL (Python Imaging Library) image library provides many common image processing and many useful basic image operations. The PIL library download address [www.pythonware.com/products/pil/].
The grayscale image is the basis of everything. The following is an example of reading an image and binarizing it (converting it to a grayscale image):
Run the code 1.1.py to get the following image:
![image](https://github.com/Nocami/PythonComputerVision-1/blob/master/image/%E5%8E%9F%E5%9B%BE%E7%81%B0%E5%BA%A6% E5%9B%BE.jpg)
### Image outline and histogram
Image outline and line contours. It is necessary to convert to a grayscale image before drawing the outline of the image, because the contour needs to acquire the pixel value of each coordinate [x, y] position.
Run 1.2.2 image outline and histogram .py to get the example shown below:
![image](https://github.com/Nocami/PythonComputerVision-1/blob/master/image/%E5%9B%BE%E5%83%8F%E8%BD%AE%E5%BB%93% E5%92%8C%E7%9B%B4%E6%96%B9%E5%9B%BE.jpg)
### Gaussian filtering (Gaussian blur, image difference)
A classic and very useful example of image convolution is Gaussian blurring of an image. Gaussian blur can be used to define image scales, calculate points of interest, and many other applications.
The 1.4.1 Gaussian Blur .py included in the runtime can get the effect of blurring the image:
![image](https://github.com/Nocami/PythonComputerVision-1/blob/master/image/%E9%AB%98%E6%96%AF%E6%A8%A1%E7%B3%8A. Jpg)
The first image above is the image to be blurred, the second image is blurred with a Gaussian standard deviation of 2, the third image is blurred with a Gaussian standard deviation of 5, and the last image is blurred with a Gaussian standard deviation of 10. For more details on the use of this module and the choice of parameters, see the SciPy scipy.ndimage document [docs.scipy.org/doc/scipy/reference/ndimage.html].
The 1.4.2 Gaussian image difference .py included in the runtime can be used to achieve differential image display:
![image](https://github.com/Nocami/PythonComputerVision-1/blob/master/image/%E5%9B%BE%E5%83%8F%E5%B7%AE%E5%88%86. Jpg)
In the above code, the first line has a standard deviation of 2, the columns represent x, y, and mag, respectively, and the second and third lines are analogous.
### Histogram equalization  
Image equalization as a pre-processing operation is a good way to normalize image intensity, and image contrast can be increased by histogram equalization.
The following is an example of the file histogram equalization displayed in the 1.5.3 histogram equalization .py file in the runtime library:
![image](https://github.com/Nocami/PythonComputerVision-1/blob/master/image/%E7%9B%B4%E6%96%B9%E5%9B%BE%E5%9D%87% E8%A1%A1%E5%8C%96.jpg)
  
 ## to sum up  
 The above is the basic part of Python image processing. It briefly introduces the concept of some terms, and attaches the py file source code and corresponding effect demonstration examples.
 Ps: The picture is nocami himself. Keep the portrait right on the picture. Please do not use it for other purposes.

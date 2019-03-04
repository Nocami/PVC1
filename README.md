# PythonComputerVision-1
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
### 直方图均衡化  
图像均衡化作为预处理操作，在归一化图像强度时是一个很好的方式，并且通过直方图均衡化可以增加图像对比度。  
下面是运行库中文件 1.3.3直方图均衡化.py 所显示的关于图片直方图均衡化的示例：  
![image](https://github.com/Nocami/PythonComputerVision-1/blob/master/image/%E7%9B%B4%E6%96%B9%E5%9B%BE%E5%9D%87%E8%A1%A1%E5%8C%96.jpg)   
  
 ## 总结  
 上述内容为python图像处理的基础部分，简单介绍了一些术语的概念，并且附上了py文件源码以及相应的效果演示示例。  
 ps：图片为nocami本人，对图片保留肖像权，请勿作他用。  



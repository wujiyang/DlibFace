## DlibFace
**face detection， face alignment and face recognition based on dlib library**

## DlibFace Solution   
包括四个项目，由于本次项目中含有人脸识别，所以必须要下载dlib-19.3及其以上版本，而且还要使用VS2015编译才行    
本次实验我下载的是当前最新dlib19.4   

之前的版本使用方法，可以参考：  
[Windows10+VS2013环境下Dlib库的编译与使用-邬小阳](http://blog.csdn.net/u013078356/article/details/54999491)  
[使用Dlib库进行人脸检测与对齐-邬小阳](http://blog.csdn.net/u013078356/article/details/54999592) 

**images文件夹为一些测试图片**   
**models文件夹为下载好的人脸对齐模型和人脸识别模型，具体链接在各个项目的测试代码中都有**  

### 1.SourceBuild  
下载dlib-19.4源码进行编译，做成静态链接库dlilib19-4，具体可参考，项目中也已经有配置了  
[dlib库的编译http://blog.csdn.net/u013078356/article/details/54999491](http://blog.csdn.net/u013078356/article/details/54999491)   

### 2.faceDetection  
 人脸检测， 将编译好的静态链接库放入项目中，其他内容具体参见项目配置  
 
### 3.faceAlignment 
 人脸对齐， 将编译好的静态链接库放入项目中，其他内容具体参见项目配置  
 
### 4.faceRecognition  
 人脸识别， 将编译好的静态链接库放入项目中，其他内容具体参见项目配置   
 
 
**模型下载位置：**   
[http://dlib.net/files/](http://dlib.net/files/)

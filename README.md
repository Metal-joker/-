# 正方验证码识别（基于TensorFlow）
<!-- TOC -->

- [正方验证码识别（基于TensorFlow）](#正方验证码识别基于tensorflow)
    - [验证码采集](#验证码采集)
    - [TensorfFlow安装](#tensorfflow安装)

<!-- /TOC -->
## 验证码采集
    pip install wget
    python getCAPTHCA.py [num]
num是指下载验证码的数量，不填的话默认3000
## TensorfFlow安装
- 安装Python3.5.2
- 安装CUDA 8.0
- 安装cuDNN 5.1 For CUDA 8.0
- 按官网教程安装TensorFlow
    - 安装完成之后import出现问题，提示缺少wrap_tensorflow模块
    - 解决方法: 把下载的cuDNN文件夹里DLL移动到CUDA的bin目录下，.h文件移动到include目录。

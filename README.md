# 作业3源码实现

 
#### 选题：A Neural Algorithm of Artistic Style（艺术风格改变）
#### 源码来源于：[https://github.com/ckmarkoh/neuralart_tensorflow](https://github.com/ckmarkoh/neuralart_tensorflow)
#### 实现语言：Python 3.6.3
#### 实现环境：

- win10 64bits
- cpu: Intel i7 6500u
- gpu: AMD r7 m360

#### 所需库：

 - [Tensorflow](http://www.tensorflow.org/)
 - [VGG 19 model](https://drive.google.com/file/d/0B8QJdgMvQDrVU2cyZjFKU1RrLUU/view?usp=sharing)

#### 实验步骤
- 此处省略一个多小时的环境搭建，包安装过程。。。
- 安装完环境和所需库后，直接命令行输入 `py main.py`即可
- 由于库要求N卡渲染，但本机为A卡，所以不得不使用cpu渲染，再加上本机性能较差，所以大概渲染了20+小时......
- 下面是渲染时的截图
![23](https://raw.githubusercontent.com/EricWWWW/A-Neural-Algorithm-of-Artistic-Style/master/img/4.png)
![23](https://raw.githubusercontent.com/EricWWWW/A-Neural-Algorithm-of-Artistic-Style/master/img/5.png)
![23](https://raw.githubusercontent.com/EricWWWW/A-Neural-Algorithm-of-Artistic-Style/master/img/6.png)
- 内容提供
![23](https://raw.githubusercontent.com/EricWWWW/A-Neural-Algorithm-of-Artistic-Style/master/img/9.jpg)
- 风格提供
![23](https://raw.githubusercontent.com/EricWWWW/A-Neural-Algorithm-of-Artistic-Style/master/img/7.jpg)
- 渲染结果
![23](https://raw.githubusercontent.com/EricWWWW/A-Neural-Algorithm-of-Artistic-Style/master/img/7.png)
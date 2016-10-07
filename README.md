### DOL的框架描述：

##### DOL是一个将半自动应用匹配到多处理器SHAPES结构平台上的一个框架，其包含三部分：

1. DOL应用项目接口：其被内置了一系列的运算和交流的程序可以运行一些被分配到SHAPES平台的项目；

2. DOL函数模拟：其作用是让程序员去运行他写的应用。

3. DOL映射优化：DOL映射优化的目的是去计算一系列在SHAPES结构平台上面的程序的优化映射。

### DOL安装笔记

*  首先通过 ' sudo apt-get update$	sudo apt-get install ant$ 	sudo apt-get install openjdk-7-jdk	sudo apt-get install unzip ' 配置安装环境。

*  利用语句‘ sudo wget http://www.accellera.org/images/downloads/standards/systemc/systemc-2.3.1.tgzsudo wget http://www.tik.ee.ethz.ch/~shapes/downloads/dol_ethz.zip ’去下载文件到虚拟机当中。

*  新建dol文件，并且将下载的安装包dolethz.zip解压到dol文件当中，同时解压systemc文件。

*  编译systemc：解压后进入systemc-2.3.1的目录下， 新建一个临时文件夹objdir，进入该文件夹，运行configure用于编译。

*  利用语句‘sudo make install’编译system，并且'pwd'指令记录下当前的工作路径。

*  编译dol文件: ' ant -f build_zip.xml all ‘.然后运行第一个例子。

   ​
### 实验感想 

     通过本次实验，完成了DOL的安装，因为TA给出的安装文档很详细，所以几乎没遇到什么问题，本次安装DOL的心得体会是要事先把所有的安装文档看一下，有些问题的解决方法会在其他类似Q&A等文档上面写明，其他方面细心按照指示就好，还有因为是初始DOL，所以对其框架结构的理解比较片面，所以要等到以后不断地学习再加深自己的理解。



   ​

   ​

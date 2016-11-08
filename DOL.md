#                             DOL实例分析及编程

## 实验任务1： 

	####  	修改example2，让3个square模块变成2个。

### 修改部分截图：

​				![img](file:///C:\Users\lenovo\AppData\Local\Temp\ksohtml\wps9E77.tmp.jpg)-->   

### 实验结果截图：

​			![img](file:///C:\Users\lenovo\AppData\Local\Temp\ksohtml\wps50D3.tmp.jpg)    

### 修改思路：

#### 	我们将squre.c文件中生成”平方器“的部分通过修改迭代次数由生成三个改为生成两个即可。

### .dot截图：

​			

​               ![img](file:///C:\Users\lenovo\AppData\Local\Temp\ksohtml\wps68B5.tmp.jpg)->

## 实验任务2：

#### 	修改example1，使其输出3次方数，tips:修改square.c 

### 修改部分的截图：

​			![img](file:///C:\Users\lenovo\AppData\Local\Temp\ksohtml\wps285F.tmp.jpg)->

### 实验结果截图：

​			![img](file:///C:\Users\lenovo\AppData\Local\Temp\ksohtml\wps89BA.tmp.jpg)->

### 修改思路：

#### 	将squre.c的i×i改成i×i×i，这样就由平方改成了立方。

### .dot截图：

​				![img](file:///C:\Users\lenovo\AppData\Local\Temp\ksohtml\wpsC03.tmp.jpg)>->

## 实验感想：

#### 	通过本次实验，分析并且修改了DOL代码，对于其中各部分的作用有了更加深刻的理解：.c与.h文件组成模块实例，.xml文件定义系统框架以及其中各模块的连接方式，本次实验当中的实例都是分为三部分，生产者消费者和一个平方函数，生产者生产数据传递给平方函数进行加工，平方函数又将处理之后的数据传递给消费者，这期间的数据通道就是有xml文件搭建起来的，我们在平方函数当中设置不同的计算方法可以来处理数据实现不同的功能，并且我们可以在.xml文件中利用迭代的方法来实现多个相同的模块，简洁方便。
















#                           ROS安装教程

## ROS安装笔记

1. 确认乌邦图权限：确认乌邦图权限允许   restricted，universe和multiverse。
2. 利用语句sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'配置资源列表。
3. 利用语句：sudo apt-key adv --keyserver hkp://ha.pool.sks-keyservers.net:80 --recv-key 0xB01FA11 配置钥匙。
4. 确认Debian包是最新的：sudo apt-get update。
5. 选择Desktop-Full Install方式安装ROS。
6. 使用ROS之前初始化rosdep：rosdep可以方便安装系统所依赖的资源并且可以编译和运行一群ROS的一些核心成分。
7. 配置环境：这是非常方便的当你每一次启动一个新的shell的时候ROS变量自动添加到你的 bash session。
8. 获取rosinstall，它可以帮助我们用一行命令快速下载ROS资源树。
9. 建立farm status。

## 实验感想

​	通过本次实验，完成了ROS的安装，安装过程中几乎没遇到什么问题，细心按照实验指导即可，现在只是安装ROS，关于其主要应用没有太多理解，需要以后通过实验不断学习。

​                         

 

   

​    

 

​               



 

 

 

​                         

 

   

​    

 

​                
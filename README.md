# Study-note from HanLin

##### *内心os：我好笨，我记不住，虽然好麻烦好麻烦，但是我得做笔记记录下来...*



本仓库包含以下内容：

1. 一些学习的[心得笔记](#心的笔记)

3. 一些可能有用的[电子书籍和学习资源](#Resource)（白嫖使我快乐）

3. 一些[学习软件](#Software)的安装（还是白嫖^_^，仅供自身学习使用，请勿外传，亲测无病毒，放心使用！）

4. 一些[杂项](#Other)

5. TODO......!^_^

## 科学上网
  科学上网是在国内了解前沿学术动态不可或缺的途径，我给大家推荐我自己常用的科学上网软件及配置方法：
  - 科学上网基本分两种方式，一种是某些公司的成品VPN app 但我不推荐，其价格比较贵，网速比较差，也不是很安全。
  - 我推荐的是使用翻墙工具加机场节点的方式实现科学上网
  - 机场推荐[MESL](https://in.mesl.cloud/#/register?code=j8NJwVyg)其价格大概是14元每月，240每年，不推荐免费节点和免费VPN
  - 有了机场节点以后就是翻墙工具，翻墙工具在不同的设备上有不同的使用方法，IOS设备（iPhone，mac）推荐使用Shadowrocket,使用美区账号下载安装导入上一步的节点即可；win和安卓设备推荐使用Clash或者圈X
  - 具体使用教程参考[MESL官方教程](https://in.mesl.cloud/#/stage/knowledge)
  
  other:
  为了自身安全及规避法律风险，科学上网方法仅可用于学术途径，勿作他用。建议大家进行一系列外网操作时使用谷歌账号或outlook账号，尽量避免使用境内邮箱。




## 心得笔记

- ### [SLAM Theory](./slam_theory/)

  - [匈牙利算法](./slam_theory/匈牙利算法.md)
  - [相机参数DKPR的解释](./slam_theory/相机参数DKPR的解释.md)
  - [多维高斯分布](./slam_theory/多维高斯分布.md)
  - [正态分布](./slam_theory/正态分布.md)
  - [灰度质心法](./slam_theory/灰度质心法.md)
  - [雅可比矩阵和海塞矩阵](./slam_theory/雅克比矩阵和海塞矩阵.md)
  - [高斯牛顿法](./slam_theory/高斯牛顿法.md)
  - [归一化与标准化](./slam_theory/归一化与标准化.md)
  - [超定方程组的最小二乘解](./slam_theory/超定方程组的最小二乘解.md)
  - [单目视觉的尺度等价性](./slam_theory/单目视觉的尺度等价性.md)
  - [多元函数的泰勒展开式](./slam_theory/多元函数的泰勒展开式.md)
  - [矩阵的奇异值分解](./slam_theory/矩阵的奇异值分解.md)
  - [为什么使用齐次坐标](./slam_theory/为什么使用齐次坐标.md)
  - [向量积(矢积)与数量积(标积)的区别](./slam_theory/向量积(矢积)与数量积(标积)的区别.md)
  - [协方差矩阵](./slam_theory/协方差矩阵.md)
  - [重投影误差](./slam_theory/重投影误差.md)
  - [多线激光雷达与组合惯导外参标定原理](./slam_theory/lidar_calibration_cn.pdf)
  - [图优化g2o](./slam_theory/图优化g2o.pdf)
  - [矩阵微分](./slam_theory/矩阵微分-清华.pdf)
  - [本质矩阵/基础矩阵/自由度及其解法](./slam_theory/本质矩阵，基础矩阵，自由度及其解法.md)
  - [2d激光雷达运动补偿方法(去畸变)](./slam_theory/2d激光雷达运动补偿方法(去畸变).md)
  - [局部规划算法DWA](./slam_theory/局部规划算法DWA.md)
  - [ros2 cost function](./slam_theory/ros2_cost_function.md)
  - [路径规划之A*算法](./slam_theory/路径规划之A-star算法.md)
  - [路径规划之Theta*算法](./slam_theory/Theta_star-Any-Angle-Path-Planning-on-Grids.md)
  - [欧拉角与坐标系旋转变换](./slam_theory/欧拉角与坐标系旋转变换.md)
  - [本质矩阵基础矩阵的自由度及其解法](./slam_theory/本质矩阵基础矩阵的自由度及其解法.md)
  - [SLAM中的位姿变换与轨迹评价指标APE、RPE、ATE、RTE](./slam_theory/SLAM中的位姿变换与轨迹评价指标.md)
  - [激光雷达性能指标](./slam_theory/激光雷达性能指标.md)
  - [二维空间中的点坐标旋转关系](./slam_theory/二维空间中的点坐标旋转关系.md)
  - ROS相关
    - [ROS指令](./C++/ROS指令.md)
    - [ROS激光雷达信息点云信息和PCL信息之间的转换](./slam_theory/ROS激光雷达信息、点云信息和PCL信息之间的转换.md)
    - [ROS Nodehandle句柄的理解](./slam_theory/ROSNodehandle句柄的理解.md)
    - [ROS param 的使用](./slam_theory/ROSparam的使用.md)
    - [ROS中Remap(话题重映射)的两种使用方法](./slam_theory/Ros中Remap(话题重映射)的两种使用方法.md)
  - 待上传

- ### [C++相关知识](./C++)
  
  - [常用函数](./C++/常用函数.md)
  - [opencv常用api](./C++/opencv常用api.md)
  - [c++并发与多线程](./C++/c++并发与多线程.md)
  - [STL容器使用时机](./C++/STL容器使用时机.md)
  - [类型转换](./C++/转换.md)
  - [Opencv_Mat](./C++/Opencv_Mat.md)
  - [const成员函数](./C++/const成员函数.md)
  - [cin与get()getline()输入问题](./C++/cin与get()getline()输入问题.md)
  - [string和cstring头文件的区别](./C++/string和cstring头文件的区别.md)
  - [常规函数与内联函数](./C++/常规函数与内联函数.md)
  - [单例模式](./C++/单例模式.md)
  - [二叉树遍历](./C++/二叉树遍历.md)
  - [构造函数的调用时机](./C++/构造函数的调用时机.md)
  - [函数指针的定义方式](./C++/函数指针的定义方式.md)
  - [计算时间](./C++/计算时间.md)
  - [类知识点](./C++/类知识点.md)
  - [内联函数](./C++/内联函数.md)
  - [数据类型字节数](./C++/数据类型字节数.md)
  - [protobuf基本使用](./C++/Protocol_Buffers基本使用.md)
  - [EigenGeometry](./C++/EigenGeometry.md)
  - [Eigen几何模块的引入](./C++/EigenGeometry.md)
  - [gflags使用](./C++/gflags使用.md)
  - [左值与右值](./C++/左值与右值.md)
  - [C++下const增强](./C++/C++下const增强.md)
  - [C++11chrono库](./C++/C++11chrono库.md)
  - [GoogleTest](./C++/GoogleTest.md)
  - Cmake相关
    - [CMakelists基础指令](./C++/CMakelists基础指令.md)
    - [CMakeLists简易模板](./C++/CMakeLists简易模板.md)
    - [find_package指令](./C++/Find_package.md)
  
- ### [SLAM配置文档](./slam_config/)

  - [ubuntu18.04系统下安装turtlebot2](slam_config/ubuntu18.04系统下安装turtlebot2.md)
  - [xavier装机文档](slam_config/xavier装机文档.md)
  - [turbot建图导航算法](slam_config/turbot建图导航算法汇总.md)
  - [Rosdep_update_falied](slam_config/Rosdep_update_failed.md)
  - [安装LIO-SAM](slam_config/安装LIO-SAM.md)
  - [安装orb-slam2](slam_config/安装Orb-slam2.md)
  - [安装Rtabmap](slam_config/安装Rtabmap.md)
  - [安装VINS-Fusion](slam_config/安装VINS-Fusion.md)
  - [安装ZED以及ros驱动](slam_config/安装ZED以及ros驱动.md)
  - [轨迹评估介绍与evo工具使用](slam_config/轨迹评估介绍与evo工具使用.md)
  - [基于ROS的opencv安装与卸载](slam_config/基于ROS的opencv安装与卸载.md)
  - [激光+imu标定(lidar_align)](slam_config/激光+imu标定(lidar_align​).pdf)
  - [激光+imu标定(lidar_imu_calib)](slam_config/激光雷达与IMU联合标定(lidar_IMU_calib).md)
  - [相机+imu标定](slam_config/相机+imu标定.pdf)
  - [激光雷达+相机标定](slam_config/激光雷达+相机标定.pdf)
  - [ubuntu18.04环境配置](./slam_config/Ubuntu18.04环境配置.md)

- ### Linux

  - 待上传

- ### [QT编程](./QT)
  
  - [项目默认文件介绍](./QT/项目默认文件介绍.md)
  - [qt点击按钮进行页面的切换](./QT/Qt点击按钮进行页面的切换.md)
  - [qt迁移项目后修改时间大于当前时间](./QT/QT迁移项目后显示修改时间大于当前时间.md)
  - [基于arm架构的NVIDIA Xavier安装Qt](./QT/基于arm架构的NVIDIA_Xavier安装Qt.md)
  
- ### 一些怎么也记不全的[command](./command/)指令
  
  - [Git_Command](./command/Git_Command.md)
  - [Git中submodule的使用](./command/Git中submodule的使用.md)
  - [Git cherry-pick的使用](./command/git_cherry-pick.md)
  - [Git rebase的两种用法](./command/git_rebase的两种用法.md)
  - [Docker简要教程](./command/Docker简要教程.md)
  - [Ubuntu-xavier](./command/Ubuntu-xavier.md)
  - [LIO-SAM运行](./command/LIO-SAM运行.md)
  - [Orb-slam2运行](./command/Orb-slam2运行.md)
  - [Velodyne_VLP16线激光雷达调用](./command/Velodyne_VLP16激光雷达调用.md)
  - [Xsens传感器调用](./command/Xsens传感器调用.md)
  - [ROS查看ZED节点此效果](./command/ROS查看ZED节点效果.md)





## Resource

#### Online Learning

- 文献检索：研究僧的好伴侣，[Sci-Hub](https://www.sci-hub.ren/)和[arXiv](https://arxiv.org/)，基本顶会论文都可以免费下载阅读。
- [Paperswithcode](https://paperswithcode.com/)：作为AI工程师（cv工程师）中的一员，这个网站可以找到许多附带开源代码的高质量论文。
- [*Z-Library*](https://zh.1lib.education/)：这个数字图书馆可以搜索下载到各种各样的电子书，十分强大，而且免费，不过需要科学上网才能访问。
- EbookFoundation开源了一个仓库[free-programming-books](https://github.com/EbookFoundation/free-programming-books)，在这里你可以找到许多编程类电子书籍和开源课程。
- [awesome-cs-books](https://github.com/imarvinle/awesome-cs-books)这个仓库包含了许多经典计算机书籍： 编程语言(Java、C++、C、Python等等)、操作系统、计算机网络、系统架构、程序员数学、测试、前端开发、后台开发、网络编程、Linux使用及内核、求职面试、算法与数据结构 安卓、IOS、数据库、Redis等主流的编程学习书籍。
- [HelloGitHub](https://github.com/521xueweihan/HelloGitHub)：HelloGitHub 每个月定期分享 GitHub 上有趣、入门级的开源项目。包含多种编程语言，有助于编程语言的学习。
- [基本素养](https://github.com/ahangchen/How-to-Be-A-Programmer-CN)：当然除了编程语言外，想要成长为一个合格的程序员还是需要具备许多其他的基本素养。
- [数据结构](https://github.com/youngyangyang04/leetcode-master)：数据结构很重要哦，毕竟也要去面试嘛，还有一个[算法可视化平台](https://github.com/algorithm-visualizer/algorithm-visualizer)，极大地提高了我自己的算法学习理解效率。
- [鸟哥的私房菜](http://cn.linux.vbird.org/linux_basic/linux_basic.php#part3)：这本书应该是不少linux开发者必读书籍吧。
- [Linux命令大全](https://www.linuxcool.com/)：当然了鸟哥的私房菜实在是过于详细，平常的学习工作中我们可能只是想要简单快速查一下某一个命令的用法。 
- [PPT模板](https://www.pptsupermarket.com/)：面向ppt编程，怎么可以没有好用的模板呢。



#### Electronic Book

- [视觉SLAM](https://pan.baidu.com/s/1yFiZ_fqGnKi7ExvMyvChgQ)	提取码：`1314`
- [深度学习](https://pan.baidu.com/s/12Y30nfWqwDqeXz6sCvZgTw)	提取码：`1314`
- [C++](https://pan.baidu.com/s/1DsBbgs2GZlxJel5cXpIOYQ)	提取码：`1314`
- [Linux](https://pan.baidu.com/s/1f_jGoBzd1ZihH_OhGTC82w)	提取码：`1314`
- [Python](https://pan.baidu.com/s/1m7_FToasf8VPln4-8jilLw)	提取码：`1314`
- [操作系统](https://pan.baidu.com/s/17eCDh-8gxEpyBoNORodYaA)	提取码：`1314`
- [分布式系统](https://pan.baidu.com/s/1GaSVK03EPcnQdH4BhcxZZA)	提取码：`1314`
- [后端组件](https://pan.baidu.com/s/1drB61wzhg7NG5L3KhOmrXw)	提取码：`1314`
- [计算机网络](https://pan.baidu.com/s/1qBYrPLhRpF_dhPXOQBRNZQ)	提取码：`1314`
- [计算机系统知识](https://pan.baidu.com/s/1I54KS6usF89NhRgagSGjeQ)	提取码：`1314`
- [前端&全栈](https://pan.baidu.com/s/1pKy4BJKc7SpRGq0Js-0t_A)	提取码：`1314`
- [数据库](https://pan.baidu.com/s/1eWlvbY0MrqRF2fI6p7kb4g)	提取码：`1314`
- [算法和数据结构](https://pan.baidu.com/s/1Xl8U-exf7lb2b9ss593_2g)	提取码：`1314`
- [网络编程&服务器开发](https://pan.baidu.com/s/1diwvkJGb2CFkonj40yvtew)	提取码：`1314`
- [面经](https://pan.baidu.com/s/1WGa1TRnHh3m1wmV4F7EkGA)	提取码：`1314`
- [面试准备](https://pan.baidu.com/s/1FCYJ-TDRfKKkHlQWSgmL3g)	提取码：`1314`



## Software

- ### Typora

  ​	作为一名程序员，强烈建议大家使用Markdown语法编写文档。它允许人们使用纯文本格式编写文档，由于 Markdown 的轻量化、易读易写特性，许多网站都广泛使用 Markdown 来撰写帮助文档， 如 GitHub等， Markdown格式同步github远程仓库十分方便，不用担心windows层出不穷的格式错误。这里推荐一款Markdown语法软件Typora，由于最近该软件开始收费了，本着学习（白嫖）的精神，因此保存了不收费的一个版本。

  - [Windows版本](https://pan.baidu.com/s/14Fftz3ECigAh-abV-7VHrw)	提取码：`1314`
  - [Linux版本](https://pan.baidu.com/s/1rAC-yfhA9-UNVo0y0AIxyg)	提取码：`1314`



- ### XMind

  ​	最好的思维导图软件，没有之一，可惜高级功能要收费，这里分享一个破解版，可以无水印导出。下载安装直接使用，破解版软件不能登录不用我多说吧，亲测无病毒，放心使用。

  - [Windows版本](https://pan.baidu.com/s/1oFZS5czuOF2hEbw1LfxgIw)	提取码：`1314`
  - [Linux版本](https://pan.baidu.com/s/1eiOgY8p2Ytlt8AaEUIHelQ)	提取码：`1314`
  - 流氓软件默认安装c盘，安装好后将破解包里的app.asar文件复制替换到Program Files/XMind/resources目录下即可。	



- ### MATLAB

  ​	MATLAB，工科生居家旅行必备。有什么好说的吗？没什么好说的吧......

  - [MATLAB](https://pan.baidu.com/s/1aH7OmFjjGApE-v0Md8aB8w)	提取码：`1314`
  - 至于详细怎么安装，请自行百度。ps：安装镜像文件，选择密钥安装，最后将补丁文件复制到软件文件夹下全部替换就可以啦O(∩_∩)O



- ### IDM

  ​	受够了百度云，迅雷的限速吗，请使用IDM下载器，还支持浏览器插件版本，天下苦百度迅雷久矣........

  - [IDM](https://pan.baidu.com/s/1vDUlk8r0bn7eb6zqnMEYkQ?pwd=1314)	提取码：`1314`
  - IDM支持百度云不限速下载助手，至于怎么用，tampermonkey插件yyds。



- ### Adobe pdf

  ​	功能最全的pdf编辑器，一键安装。

  - [Adobe pdf](https://pan.baidu.com/s/1Fz0iAbfkJAFFD0ye20nvVA)	提取码：`1314`
  - Adobe系列版本越高对电脑配置要求越高，所以全家桶都有点卡顿，但不影响正常使用。附[Adobe全家桶](https://pan.baidu.com/s/1SYvUb4AeAQ5R6Lq6xypQNw)	提取码：`1314`



- ### Pycharm

  ​	Python IDE推荐，我是JetBrains家一系列开发工具的忠实使用者，主要优点：与时俱进，界面优美，功能强大。你还在为同步GitHub仓库发愁吗，你还在为ssh链接服务器痛苦吗，Pycharm一键注册99年，从此告别Mobxterm。

  - [Pycharm(windows版本)](https://pan.baidu.com/s/11syiJLEngQL3-8pzqshe7w)	提取码：`1314`
  - 将注册机拖到pycharm里一键完成注册即可。



- ### Office全家桶

  ​	office是目前最常用的一类办公软件，使用它可以解决日常生活和工作中遇到的很多问题。里面包含了常用的办公组件而其中就包含了Word、Excel、PowerPoint、Access等。熟练掌握offic的操作技巧是对计算机工作者的基本要求,也可以帮助你提高工作效率出色的完成企业办公需求!新版的Office与之前的老版本相比，不仅是界面上有所改进，同时在功能上也带来一些新特性!

  - [Office全家桶](https://pan.baidu.com/s/1LJo45XDnsSltjNCaiWT0MQ) 提取码：`1314`
  - [破解教程](./something_else/获取Office2021安装包及相关激活工具.md)







## 维护者

[@HanLin](https://github.com/hanlin-cheng)

[@Kikoo](https://github.com/wutujiu)
> *关山难越，谁悲失路之人。萍水相逢，尽是他乡之客。*




### 一、Description
> DOL 框架描述(随着实验进行迭代添加、修改)
> ![](http://ww2.sinaimg.cn/mw690/005Fy6Kggw1f8mafk9mx9j30rz0fcgnr.jpg)


### 二、How to install
#### DOL安装笔记

>2.1 安装一些必要的环境：
$	 sudo apt-get update
$     sudo apt-get install ant
$     sudo apt-get install openjdk-7-jdk
$	 sudo apt-get install unzip
   通过”ctrl”+”alt”+”T”调出终端并输入相关代码即可
   
>2.2 解压dol文件夹和systemc，要注意如果之前从主机拷贝到虚拟机的dol_ethz.zip和systemc-2.3.1.tgz是放在桌面的，要先通过“cd Desktop”进入到桌面。
> ![](http://ww4.sinaimg.cn/mw690/005Fy6Kggw1f8mafktuxpj30hu030aai.jpg)

>2.3 运行configure之后的截图
>![](http://ww3.sinaimg.cn/mw690/005Fy6Kggw1f8mafm43vnj30j104qwfl.jpg)

>2.4 sudo make install
>编译完后文件目录如下($ cd ..        $ ls
>![](http://ww3.sinaimg.cn/mw690/005Fy6Kggw1f8mafm43vnj30j104qwfl.jpg)

>2.5 工作路径为 /home/darren/Desktop/systemc-2.3.1
>![](http://ww4.sinaimg.cn/mw690/005Fy6Kggw1f8mafmok8yj30db0100sp.jpg)

>2.6 编译 $	ant -f build_zip.xml all
>若成功会显示build successful
>![](http://ww2.sinaimg.cn/mw690/005Fy6Kggw1f8mafnckd4j30b902qwei.jpg)

> 2.7 运行第一个例子
> ![](http://ww4.sinaimg.cn/mw690/005Fy6Kggw1f8mafo3f7vj30f20ce0ud.jpg)

### 三、Experimental experience
>实验感想、实验心得
在完成下述三步时先要确定进入dol_ethz.zip和systemc-2.3.1.tgz所在文件夹：
新建dol的文件夹 
$	mkdir dol
将dolethz.zip解压到 dol文件夹中
$	unzip dol_ethz.zip -d dol
解压systemc
$	tar -zxvf systemc-2.3.1.tgz




                 


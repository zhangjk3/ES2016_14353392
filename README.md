# **DOL开发环境配置**
## Description
***
## How to install
***
1. 因为上学期使用过Ubuntu学习pintos，所以很多环境已经配置好了。按照PPT上的教程，一步一步也没有出问题。
2. 安装环境

`sudo apt-get update //更新应用商店（或者说应用库）
sudo apt-get install //安装ant
sudo apt-get install openjdk-7-jdk //安装Java库
sudo apt-get install unzip //安装解压软件，这个我之前就有`
3. 用刚刚装好的解压软件进行解压，并放入dol文件夹

`mkdir dol
unzip dol_ethz.zip -d dol
tar -zxvf systemc-2.3.1.tgz`
4. 编译systemc
###因为上上周做的实验，当时没有截图，所以只能空口说了。具体过程就是按照PPT上。
5. 编译dol 
###这个也是按照PPT上做的，我的系统是32位的，所以直接找到systemc文件，然后修改地址即可
6. 编译样例如下图

![QQ截图20161010014955.png](http://upload-images.jianshu.io/upload_images/3254023-cd4d04a1a095ad66.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![QQ截图20161010015413.png](http://upload-images.jianshu.io/upload_images/3254023-b1078bd4bd38e5ca.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
## Experimental experience
***

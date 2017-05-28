# Python-Learning
This is a journey of my Python 3 learning
What you need to know shows below:
Python 3.x Environment Install on Linux
  1. 源代码下载：wget https://www.python.org/ftp/python/3.6.1/Python-3.6.1.tar.xz
  2. 解压文件：tar xJf Python-3.6.1.tar.xz  #J为xz格式的解压
  3. 配置前安装必要的库，以避免安装后的Python出现的一些问题：
  yum install readline-devel.x86_64
  （或直接yum install readline-devel）
  4. 切换到Python-3.6.1目录下：cd Python-3.6.1
  5. 配置：./configure
  6. 编译：make
  7. 安装：make install
  8. 使用：python3
  	[root@localhost Python-3.6.1]# python3
	Python 3.6.1 (default, May 14 2017, 04:57:23) 
	[GCC 4.8.5 20150623 (Red Hat 4.8.5-11)] on linux
	Type "help", "copyright", "credits" or "license" for more information.
	>>>

二、 Python Modules Files Install
  1. 将.py后缀的模块文件放入到/usr/lib/python2.x(3.x)/site-packages/目录下即可

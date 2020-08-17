
# centos下安装bs4

图灵这版的《python网络爬虫权威指南》中第六页介绍的安装bs4的方法，仅限于linux的ubuntu系统。
初入linux和python，为了成功安装走了很多弯路，解决办法以及过程如下。

因为传说中的不兼容等等问题，在建议下使用了docker。

- 先安装pip(python负责模块的部分 一般安装python都会有pip)
- 再安装bs4  pip install beautifulsoup4

运行：

- docker images 列出本地镜像
- docker run -it -v /home/user/home/user  python:3.7 "/bin/bash"   语句顺序先后问题 [option]在前commands在后 (docker -h)
- cd /home/user/crawler
- python test.py

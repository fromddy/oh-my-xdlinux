oh-my-xdlinux
==========================

`oh-my-xdlinux` is a script for automating using XDLINUX mirrors when applicable.

Usage
==========================

The simple way:
```bash
最新版本还没有上传到这个网站
wget https://rawgit.com/xdlinux/oh-my-xdlinux/master/oh-my-xdlinux.py
python oh-my-xdlinux.py
```



Change system-wide settings instead of user-wide:
```bash
sudo python3 oh-my-xdlinux.py -g -v 
-v 的含义是 verbose 即显示更加丰富的信息
-g 的含义是 提升到全局的权限 
执行这条命令，除了PyPi其他的都会转化为西电源

如果想要让Pypi为西电源的话(目前是会转到清华源下载）
python oh-my-xdlinux.py 
```

Get help:
```bash
python oh-my-xdlinux.py -h
```

Uninst all off the mirrors.
```bash
sudo python3 oh-my-xdlinux.py -g -v down
除了PyPI其他的所有源的镜像都会转到

sudo python oh-my-xdlinux.py -v down
卸载掉PyPI的源镜像
```






Coverage
=========================
 - Homebrew
 - CTAN
 - Anaconda
 - PyPI
 - CTAN
 - TeX Live (by tlmgr)
 - Arch Linux
 - Debian
 - Ubuntu
 - Kali
 - Deepin
 - Centos


 
 
TODO
========================
do more test on different platforms


 

License
==========================

Licensed under GNU General Public License 3.0

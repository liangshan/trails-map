GNU/Linux
=========

介绍
----

如果您已经是使用Unix、BSD的用户，或者熟悉MacOSX的命令行，那么推荐您看一下[这篇文章][1]。

关于Linux，您需要先了解[什么是Linux][2]。

如果您是一位计算机的初学者，或者不熟悉什么叫做[命令行][3]，建议您使用[入门方法][4]。

而如果对自己有自信，想寻找一些挑战，您可以选择[the hard way][5]。

记住，

> 更困难的方式总是让您有更多的回报 -- 未知


XDDDDDDDDDDDD

the easy way
------------

### 挑选发行版

有不少发行版比较适合Linux新手，它们带有图形界面、安装简单、系统管理比较符合图形用户的习惯。

* [ubuntu](http://www.ubuntu.com)
* [mint linux](http://linuxmint.com/)
* [Fedora](http://fedoraproject.org/)
* [OpenSUSE](http://www.opensuse.org/)
* [Mandriva](http://www.mandriva.com/)
* [PCLinuxOS](http://www.pclinuxos.com/)

### 学习

* 使用livecd运行! 不少Linux发行版都提供了LiveCD，可以直接从CD/DVD启动而不影响现有系统
* 学会如何把Linux安装到您的PC里，第一步您可以让她原有的操作系统共存
* 学会一些常用的操作软件，例如
  * 选择您喜欢的编辑器，例如gedit / kate 等
  * 选择您喜欢的浏览器，例如Firefox / Google Chrome / Midori / Konqure
  * 选择您常用的办公软件，例如Libreoffice
* 学会如何输入中文
* 学会配置网络，顺利访问网络
* 学会如何访问windows网络共享
* 学会如何配置打印机、闪盘等硬件设备
* 学会如何播放音乐、电影等多媒体文件
* 学会如何查看系统状态
* 学会安装软件
* 知道什么是[root用户](http://zh.wikipedia.org/wiki/%E8%B6%85%E7%BA%A7%E7%94%A8%E6%88%B7)
* 了解Linux的[文件树](http://soft.zdnet.com.cn/software_zone/2008/0626/950668.shtml)
* 了解[用户、组，和文件的权限](http://linux.chinaitlab.com/administer/38992.html)
* 学会打开命令行界面
* 学会以下这些命令

```
cd
ls
pwd
cp
mv
rm
mkdir
rmdir
which
chmod
chown
echo
find
locate
ps
kill
sort
tail
head
cat
top
vmstat
man
```

* 学会管道 (`|`)
* 学会重定向 (`>`, `<`, `>>`)
* 学会如何[进程控制](http://www.cnblogs.com/zhouyinhui/archive/2010/09/09/1822594.html)
* 学会[简单的shell脚本编程](http://tech.ddvip.com/2007-03/117369749720969.html)
* 阅读[「The Linux Command Line」](http://linuxcommand.org/tlcl.php) (英语)
* 阅读[「鸟哥的Linux私房菜」](http://vbird.dic.ksu.edu.tw/)
* 阅读[「Linux权威指南」](http://book.douban.com/subject/1052714/) ($)

### 检验

如果您觉得自己已经入门了，您应该可以

* 安装并顺利进入Linux系统
* 知道在其他系统里的软件，在Linux应该使用什么软件
* 知道如何配置网络，并能够顺利访问网络

如果您觉得自己运用已经比较熟练，您应该可以

* 知道如何配置常用硬件
* 知道如何查看系统当前状态
* 知道如何安装、卸载软件

如果您觉得已经更进一步，您或许还能够

* 知道命令行是什么
* 能够在命令行下做一些常用的操作
* 会写简单的shell脚本
* 或许还会对the hard way里的内容也感兴趣? XDDDDD

the hard way
------------

### 挑选发行版

选择一种优秀的发行版，适合您的使用习惯，这些发行版对使用者有更高的要求，知道自己需要什么样风格的系统。

* [gentoo](http://www.gentoo.org/)
* [archlinux](http://www.archlinux.org/)
* [debian](http://www.debian.org/)
* [slackware](http://www.slackware.com/)
* [linux from scratrch](http://www.linuxfromscratch.org/lfs/)

LFS比较特殊，从头构建一个Linux系统，需要一个可以运行的Linux系统，7.0以前可以使用提供的LiveCD，而7.0开始LiveCD暂不可用

当然，不使用这些发行版也丝毫不影响您学习Linux的过程

### 学习

#### 基本篇

* 学会您认为应该学会easy way里的全部
* 知道Linux其实是指[Linux核心](http://zh.wikipedia.org/zh/Linux%E5%86%85%E6%A0%B8)，而常见的系统都是使用核心，外围程序、工具，是用户能够访问硬件，完成自己的工作
* 知道Linux的几乎所有工作都是可以在命令行下完成的
* 知道什么是[包管理器](http://zh.wikipedia.org/zh/%E8%BD%AF%E4%BB%B6%E5%8C%85%E7%AE%A1%E7%90%86%E7%B3%BB%E7%BB%9F)，知道自己所使用发行版的包管理器是什么

#### 安装、硬件相关篇

* 知道什么是[boot loader](http://zh.wikipedia.org/zh/%E5%95%9F%E5%8B%95%E7%A8%8B%E5%BC%8F)
* 知道什么是[文件系统](http://zh.wikipedia.org/wiki/%E6%96%87%E4%BB%B6%E7%B3%BB%E7%BB%9F)

#### 软件篇

* 学会以下命令的使用

```
sed
awk
```

* 按需求学会以下软件的使用

```
emacs
vim
```

* 知道什么是[环境变量](http://zh.wikipedia.org/wiki/%E7%8E%AF%E5%A2%83%E5%8F%98%E9%87%8F)
  * 知道下列环境变量的作用

```
PATH
HOME
TERM
MAIL
SHELL
EDITOR
PAGER
LANG
LC_ALL
CHOST
CFLAGS
CPPFLAGS
CXXFLAGS
LDFLAGS
```

#### 图形篇

* 知道Linux的图形是基于[X-window](http://zh.wikipedia.org/wiki/X_Window%E7%B3%BB%E7%B5%B1)的，并且知道X-window是基于服务器-客户端模型的
* 知道什么是[桌面环境](http://zh.wikipedia.org/wiki/%E6%A1%8C%E9%9D%A2%E7%8E%AF%E5%A2%83)
* 知道桌面环境不仅有Gnome、KDE
* 知道什么是[窗口管理器](http://zh.wikipedia.org/wiki/%E7%AA%97%E5%8F%A3%E7%AE%A1%E7%90%86%E5%99%A8)

#### 系统篇

* 知道Linux下常见软件都是开源、可以自己编译
* 知道什么是[编译器](http://zh.wikipedia.org/wiki/%E7%B7%A8%E8%AD%AF%E5%99%A8)、[连接器](http://zh.wikipedia.org/wiki/%E9%93%BE%E6%8E%A5%E5%99%A8)
* 知道[make的作用](http://zh.wikipedia.org/wiki/Make)
* 知道[什么是工具链](http://zh.wikipedia.org/zh/%E5%B7%A5%E5%85%B7%E9%8F%88)
* 知道[什么是coreutils](http://zh.wikipedia.org/wiki/Coreutils)
* 知道[什么是binutils](http://zh.wikipedia.org/zh/GNU_Binutils)
* 学会如何从源代码安装软件
* 学会[如何编译Linux核心](http://blog.csdn.net/youyoufengxinzi/article/details/1516263)

#### 编程篇

* 学会一种[shell语言](http://zh.wikipedia.org/wiki/Unix_shell)
* 学会一种除了shell以外常见的[脚本语言](http://zh.wikipedia.org/wiki/%E8%84%9A%E6%9C%AC%E8%AF%AD%E8%A8%80)

### 检验

如果您觉得自己已经入门了，您应该可以

* 工作环境切换到Linux环境下
* 解决常见的系统故障，例如软件错误、网络问题等
* 能够无障碍地在命令行下完成常见工作
* 懂得及时求助man，翻手册，确认参数的用法

如果您觉得自己运用已经比较熟练，您应该可以

* 熟练地使用包管理器，安装、卸载软件，升级系统
* 在命令行熟练查看系统当前配置、状态，管理它们
* 知道如何处理定时任务
* 会从源代码编译安装软件

如果您觉得已经更进一步，您或许还能够

* 熟练使用vim或者emacs
* 您或许已经不再使用Gnome、KDE、Xfce等常见DE
* 会给使用地发行版打包软件，发布
* 通过脚本解决大部分日常工作

当您觉得自己比较深入了，您或许

* 使用源代码发行的Linux，例如LFS
* 构建自己的工具链
* 知道编译参数的优化
* 选择核心的功能
* 使用核心以及库来开发自己的软件

### 参考资料

* [「Unix环境高级编程」](http://book.douban.com/subject/1788421/) ($)

[1]: http://security.zdnet.com.cn/security_zone/2008/0703/962834.shtml
[2]: http://zh.wikipedia.org/wiki/Linux
[3]: http://zh.wikipedia.org/wiki/%E5%91%BD%E4%BB%A4%E8%A1%8C
[4]: #the-easy-way
[5]: #the-hard-way


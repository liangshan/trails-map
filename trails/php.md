PHP
==========

学习
----------
#### 通用资源
* 阅读[pear coding standards](http://pear.php.net/manual/zh/standards.php)
* 时刻查询[官方PHP手册](http://www.php.net/manual/zh/index.php)
* 完成[w3school](http://www.w3school.com.cn/php/php_intro.asp)的PHP教程
* 使用一个流行的开源框架： [yiiframework](http://www.yiiframework.com/), [CodeIgniter Framework](http://codeigniter.com), [Zend Framework](http://http://framework.zend.com/)
, [CakePHP Framework ](http://cakephp.org)
* 阅读[php设计模式](http://book.360buy.com/10157324.html)(￥)

#### Anjuke内部的一些资源
* 阅读[V2代码规范](http://projects.dev.anjuke.com/trac/sites/wiki/v2/CodingGuidelines)
* 可使用官方PHP手册的[镜像](http://phpdoc.corp.anjuke.com/manual/zh/index.php)来改进访问体验
* 学习V2框架。可以自行创建分支，实现安居客现有项目或是自己想玩的功能

验证
----------
你已经入门，当你能：

* 拥有良好的编码风格。不同公司风格或许不同，但在同一项目中，风格需保持一致
* 用`array`初始化数组和哈希数组，并理解他们的不同
* 掌握`array`的合并、去重、反转、删除、追加等常用操作
* 掌握字符串查找、替换、截取的技巧，以及转换字符串的编码
* 用`for`和`foreach`迭代不同数据结构的集合
* 获取系统当前时间并将其转换成不同的格式
* 运算加、减、乘、除、平方、平方根、正弦、余弦、阶乘、倒数、取模，并将运算结果四舍五入至2位小数，整数部分如果不满10位，用0填充左边
* 读取一个文本文件，在文件末尾追加内容，并最终将所有内容另存为一份HTML文件
* 合理利用`Session`和`Cookie`存储一些有意义的内容，并了解他们之间的区别
* 理解[Syntax Exam](http://www.blueshoes.org/en/developer/syntax_exam/)中的全部题目，并在开发中时刻留意关于`true`和`false`的判断
* 使用`CURL`发起HTTP请求
* 能够使用GD库和ImageMagick库来处理图片
* 了解如何快速、准确的调试PHP代码
* 了解MVC，为何需要MVC，PHP通常如何实现MVC
* 了解如何防御web开发中基本的安全问题

你已经更进一步，当你能：

* 了解在PHP中如何用`IPC`和`Socket`实现进程间通信
* 了解PHP中的闭包和命名空间
* 使用[ORM](http://zh.wikipedia.org/zh/%E5%AF%B9%E8%B1%A1%E5%85%B3%E7%B3%BB%E6%98%A0%E5%B0%84)访问数据库
* 了解如何使用设计模式来优化自己的代码
* 知道如何[编写可测试的代码](http://www.ibm.com/developerworks/cn/opensource/os-refactoringphp/?cmp=dwnpr&cpb=dw&ct=dwcon&cr=cn_Chinabyte_dr&ccy=cn)
* 了解PHP和Apache协作的方式，了解php-fpm
* 自行开发PHP扩展


Anjuke V2框架额外练习：

* 一次请求到达V2后的工作流程
* 结合[APS](http://arch.corp.anjuke.com/blog/2011/07/16/aps/)，实现异步请求（进程间通信）
* 了解V2如何加载静态资源

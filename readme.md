项目说明
====

开始学习php！！加油！！！

```php
<?php

echo 'Hello World!';

?>
```

#### 【一阶段】学习计划安排

1. 初步认识网站开发，对环境等有初步的了解:

* 知道php程序是如何运行起来的，写个最简单的列子跑起来，有个直观的印象；
* 常见的环境有哪些？都是做什么的？基础环境apache、php，搭配的数据mysql，常用的缓存redis。。。
* php如何和html交互

2.基础php语法：

* 常用数据类型
* 一些特殊类型的使用和区别，如null、false等的区分
* 运算类型熟练，如赋值、比较、运算等
* 条件语句
* 循环语句，重点是foreach、switch


3.php重点数据结构：数组array熟悉

4.php面向对象知识：

* 函数
* 类与对象

5.PHP使用mysql数据库

6.结合以前学的知识，写个小的留言板，实现以下功能：

* 留言板表单，可以填写如下类型的内容：标题（字符串）、手机号码（数字型）、联系人（email）、内容（长文本）
* 留言板接收程序，对接收到的信息进行处理，判断类型、内容是否全，如果完整，则存储下来，不对则返回错误提示
* 留言板列表页，根据发表留言时间倒序查看最新留言


#### 【二阶段】学习计划安排

1. 分析第一阶段的留言板有以下问题：

* 奥巴马发布了留言，宣传万恶的资本主义，怎么可以！！  => 限制登录后才可以发飙，增加注册、登录功能
* 好了，奥巴马登录后可以一直发，太恐怖了。。。 ＝> 使用缓存限制用户发飙留言频率，包含验证码原理
* 列表页越来越长了，怎么办 ＝> 分页原理，包含异步分页
* 辛辛苦苦写了一堆留言，一提交报错手机号填错了，回来全没了，摔！！太打击人了 ＝> 异步交互，包含正则表达式
* 老板说：棉棉啊，我要查哪些人留言了“返利”两个字！可是留言越来越多，查起来越来越慢  => 常见优化，包含db优化、sphinx搜索引擎
* 老板说：绵绵啊，我经常出差，路上我想用我的土豪金邮件实时查看最新留言！是不是狂吧酷炫拽？！ ＝> 使用smtp发送邮件
* ...

2. 注册、登录功能实现，cookie & session
3. 验证码原理
4. 分页
5. js基础，jquery基础
6. 常见优化方法：db优化、缓存、搜索优化
7. smtp发送邮件



#### 【三阶段】学习计划安排

```php
<?php

echo '这么快就到这里了？不科学!';

?>
```

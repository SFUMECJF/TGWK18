

[TOC]



# 课程信息
大作业是建立一个个人网站！

本课程首先介绍前端 Web 架构，然后继续介绍 HTML 和 CSS 中的静态网页。然后介绍 JavaScript 和 Node.js，教学生实现动态网页，为不同的客户端生成不同的 HTML，用户可以在这些网页上通过表单输入信息并将数据发送回服务器。重点放在 cookie、会话、数据库使用和安全性上。

Python+express后端占小部分。

# 适合人群
零基础想建立个人网站的人群（可以没有任何编程基础）。

# 课程评价
少有的可以教授前端建立个人网站的课程。从零基础讲起，lab没有，有一些关于三大前端语言的小练习。学完本课可以获得：

- 客户端-服务器通信和 HTTP - HTML - CSS 和 CSS 框架 - JavaScript - Node.js 和节点包管理器 - 框架和相关技术 - 表单、cookie 和会话 - 安全

视个人基础，大概需要200到300小时左右的学习时间。

# 1 评分标准
## 1.1 缩进一致
所有文件保持一致的缩进，无所谓各种缩进的好坏。但是要一致。
## 1.2 代码风格
大括号，注释，最大行的长度。语句间的空格等
## 1.3 命名习惯
宏使用全大写，变量使用小写字母，下划线风隔，函数名等等。这里可以使用谷歌的代码风格。[谷歌代码风格](https://zh-google-styleguide.readthedocs.io/en/latest/google-python-styleguide/python_style_rules/#id21)
### 1.4 命名助记
变量的命名要使得读起来要相当好理解。最好[又短又好理解](https://eng.libretexts.org/Bookshelves/Computer_Science/Programming_Languages/Book:_Python_for_Everybody_%28Severance%29/02:_Variables_Expressions_and_Statements/2.12:_Choosing_Mnemonic_Variable_Names)，不超过3个单词。
### 1.5 不使用魔法值
不要使用光秃秃的数字，而是使用描述性的常量名字来保存数字。直接出现在代码中的数字就叫魔法值。
### 1.6 资源
对游客的帖子信息等具有CRUD的功能。
### 1.7 数据库设计
坏习惯：
- 把所有的数据储存在一张表格中。

好习惯：
- 使用合理的主键约束
- 唯一约束和外部主键约束使用合理
- 数据类型合理，比如boolean, unix timestamp

### 1.8 验证
用户输入的所有数据都需要做验证。比如数字范围，字符串长度。大小写等等
### 1.9 异常处理
所有可能出现的错误，都要处理
### 1.10 图形界面
适配不同的屏幕大小，控件，鼠标，键盘等。
### 1.11 有意义的html
合理使用各类html标签。不单纯是为了人类可读。还有便于搜索引擎理解页面。
使用xhtml
1. 不使用br标签。
The main reason for not using <br> is that it's not semantic. If you want two items in different visual blocks, you probably want them in different logical blocks. In most cases this means just using different elements, for example <p>Stuff</p><p>Other stuff</p> , and then using CSS to space the blocks out properly.
2. 使用标签，对图片 使用alt描述

### 1.12 CSS
CSS选择器等合理使用
### 1.13 安全
处理sql注入等各种安全问题，XSS, CSRF，验证用户信息。不使用明文而是jwt等方法储存密码。使用session

### 1.14 报告
问题是什么以及如何解决
### 1.15 可选任务
#### 1 搜索
使用时间范围等方式实现对所有资源内容的搜索。

#### 2 分页
对资源进行分页。不太懂这里是什么操作
#### 3 上传文件
不止是使用资源或者数据库来保存文件。使用文件系统，储存文件。



## 互相交流


读者你好！如果你对本文内容感兴趣，我十分希望能够和你互相学习，可以扫码和我联系！一起进步



![在这里插入图片描述](https://img-blog.csdnimg.cn/20200529103009878.gif#pic_center)

# TGWK18

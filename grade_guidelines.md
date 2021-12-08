

[TOC]



## 1 评分标准
### 缩进一致
所有文件保持一致的缩进，无所谓各种缩进的好坏。但是要一致。
### 代码风格
大括号，注释，最大行的长度。语句间的空格等
### 命名习惯
宏使用全大写，变量使用小写字母，下划线风隔，函数名等等。这里可以使用谷歌的代码风格。[谷歌代码风格](https://zh-google-styleguide.readthedocs.io/en/latest/google-python-styleguide/python_style_rules/#id21)
### 命名助记
变量的命名要使得读起来要相当好理解。最好[又短又好理解](https://eng.libretexts.org/Bookshelves/Computer_Science/Programming_Languages/Book:_Python_for_Everybody_%28Severance%29/02:_Variables_Expressions_and_Statements/2.12:_Choosing_Mnemonic_Variable_Names)，不超过3个单词。
### 不使用魔法值
不要使用光秃秃的数字，而是使用描述性的常量名字来保存数字。直接出现在代码中的数字就叫魔法值。
### 资源
对游客的帖子信息等具有CRUD的功能。
### 数据库设计
坏习惯：
- 把所有的数据储存在一张表格中。

好习惯：
- 使用合理的主键约束
- 唯一约束和外部主键约束使用合理
- 数据类型合理，比如boolean, unix timestamp

### 验证
用户输入的所有数据都需要做验证。比如数字范围，字符串长度。大小写等等
### 异常处理
所有可能出现的错误，都要处理
### 图形界面
适配不同的屏幕大小，控件，鼠标，键盘等。
### 有意义的html
合理使用各类html标签。不单纯是为了人类可读。还有便于搜索引擎理解页面。
使用xhtml
1. 不使用br标签。
The main reason for not using <br> is that it's not semantic. If you want two items in different visual blocks, you probably want them in different logical blocks. In most cases this means just using different elements, for example <p>Stuff</p><p>Other stuff</p> , and then using CSS to space the blocks out properly.
2. 使用标签，对图片 使用alt描述

### CSS
CSS选择器等合理使用
### 安全
处理sql注入等各种安全问题，XSS, CSRF，验证用户信息。不使用明文而是jwt等方法储存密码。使用session

###  报告
问题是什么以及如何解决
### 可选任务
#### 搜索
使用时间范围等方式实现对所有资源内容的搜索。

#### 分页
对资源进行分页。不太懂这里是什么操作
#### 上传文件
不止是使用资源或者数据库来保存文件。使用文件系统，储存文件。



## 互相交流


读者你好！如果你对本文内容感兴趣，我十分希望能够和你互相学习，可以扫码和我联系！一起进步



![在这里插入图片描述](https://img-blog.csdnimg.cn/20200529103009878.gif#pic_center)


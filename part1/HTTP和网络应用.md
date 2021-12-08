

[TOC]



##  资源和URIs

服务器后台上需要以下的资源：

- Images (`.png` files, `.jpeg` files, etc.)
- Sounds (`.mp3` files, etc.)
- Videos (`.mp4` files, etc.)
- Documents (`.pdf` files, `.docx` files, `.txt` files, etc.)
- Static webpages (`.html` files, `.css` files, `.js` files, etc.)
- General data, such as:
  - Accounts
  - Blogposts
  - Guestbook posts
  - Articles
  - Private Messages
  - Comments
  - etc.



通过*Uniform Resource Identifier* (URI)定位资源，然后做增删查改。

## HTTP

结构：

```
METHOD URI VERSION
HEADER1: VALUE1
HEADER2: VALUE2
...

BODY
```
下面这句话怎么理解呢？ 
```
PUT and DELETE not in HTML

In the language used to build web pages, HTML, it's only possible to send GET and POST requests. Therefore, web developers rarely use PUT and DELETE requests. On websites, PUT and DELETE requests are often implemented as POST requests, and the URI is used to indicate if it should be a create, update or a delete operation.
```

就是我们在写html的时候，尽量只用GET和POST指令。因为不可能给权限修改服务器的。

response:

```html
VERSION STATUS_CODE REASON_PHRASE
HEADER1: VALUE1
HEADER2: VALUE2
...

BODY
```

### status code

1XX：不重要，可以不管。

2XX：成功执行请求。

- 200 OK : 

3XX: 需要重定向URI获取资源

4XX: 客户端那里的错误，服务端没执行请求。

5XX：服务器端的错误，可能是服务端flask写的代码有问题

## 互相交流


读者你好！如果你对本文内容感兴趣，我十分希望能够和你互相学习，可以扫码和我联系！一起进步



![在这里插入图片描述](https://img-blog.csdnimg.cn/20200529103009878.gif#pic_center)


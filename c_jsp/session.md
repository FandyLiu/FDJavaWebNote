# session对象

### 创建及获取客户的会话
```
// set
session.setAttribute("username", "绿草");


// get
String user =(String)session.getAttribute("username");

String user =session.getAttribute("username").toString();

```
### 在会话中移动指定绑定对象

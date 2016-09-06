# lesson 指令标识
<%@ 指令名 属性 1="属性值1" 属性 2="属性值2"....%>

如
```
<%@ page language="java" contentType="text/html; charset=UTF-8"
    pageEncoding="UTF-8"%>
```

### page 指令
<%@ page attr1 = "value1" attr2 = "value2" ...%>
包含15个属性

![](imgs/attr1.png)
![](imgs/attr2.png)
![](imgs/attr3.png)
![](imgs/attr4.png)


### include 指令

![](imgs/include.png)

```
<body style = "margin: 0px;">

<%@ include file = "top.jsp" %>

<table width = "781" height = "279" border = "1" cellspacing = "0" >
<tr>
<td>&nbsp;</td>
</tr>

<%@ include file ="copyright.jsp" %>

</table>
</body>
```


### taglib 指令
![](imgs/taglib.png)



# HTML常用标签
## 1.`<a> `
* `<a>`标签是一个超级链接，内部不仅可以放置文字，也可以放置其他元素，比如段落、图像、多媒体等等。
* `<a>`标签有如下属性。
1. `href`属性给出链接指向的网址。
2. `targt`属性指定如何展示打开的链接。他的取值有`_blank`：新窗口打开,`_self`：当前窗口打开,`_parent`：上层窗口打开，`_top`：顶层窗口打开。
3. `download`属性表明当前链接用于下载
4. `rel`属性说明链接与当前页面的关系。
* 伪协议
1. `javascritp:;`什么都不做的链接
2. `mailto：`邮箱
3. `tel:`手机号
## 2.`<table>`
* `<table>`是一个块级容器标签，所有表格内容都要放在这个标签里面。
* `<thead>、<tbody>、<tfoot>`都是块级容器元素，且都是`<table>`的一级子元素，分别表示表头、表体和表尾。
* `<tr>`标签表示表格的一行
* `<th>`和`<td>`都用来定义表格的单元格
* 相关样式
```CSS 
   table-layout
   border-collapse
   border-spacing   
   ```
## 3.`<img>`
* `<img>`标签用于插入图片。作用是发出请求展示图片
* `<img>`标签有如下属性。
1. `<alt>`属性用来设定图片的文字说明。
2. `<width>`属性用来指定图片宽度
3. `<height>`属性用来指定图片长度
* 事件 `<onload><onerror>`监听图片是否成功
* 响应式     max-width:100%
  

  
   
   

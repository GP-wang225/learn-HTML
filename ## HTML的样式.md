/## HTML的样式
用`style`属性来进行表示
### 背景颜色（包括标题、段落背景色）
```html
<body style="background-color:yellow">
<h2 style="background-color:red">This is a heading</h2>
<p style="background-color:green">This is a paragraph.</p>
</body>
</html>
```
---
### 字体、颜色、大小
`font-family` `color` `font-size`
```html
<html>
<body>
<h1 style="font-family:verdana">A heading</h1>
<p style="font-family:arial;color:red;font-size:20px;">A paragraph.</p>
</body>
</html>
```
### 文本对齐
`style="text-align:center"`
### 文本格式化
1. `sub`定义下标字体 `sup`定义下标字体
```html
x<sub>2</sub>
```
2. `ins`定义插入字`del`定义删除字

   <img src="C:\Users\DELL\AppData\Roaming\Typora\typora-user-images\image-20191230205723120.png" style="zoom:80%;" />
### 引用
1. 短引用
`<q></q>`
2. 长引用
`<blockquote></blockquote>`
3. 用于联系信息的 HTML 
`<adress></adress>`
### 计算机代码元素

1. 定义键盘输入`<kbd>`
2. `<samp>`定义计算机输出
3. `<code>` 元素定义编程代码示例不保留多余的空格和折行
4. 如需解决上面问题，您必须在 `<pre>` 元素中包围代码
### 注释
`<!`注释的内容`>`
注释不会出现在网页中
> 对于 HTML 纠错也大有帮助，因为您可以一次注释一行 HTML 代码，以搜索错误 

### css先空着
### 链接
我们通过使用 `<a>` 标签在 HTML 中创建链接。
1. 通过使用 `href `属性 - 创建指向另一个文档的链接
    1.1 `<a href="url">Link text</a>` 
    1.2 使用 Target 属性，你可以定义被链接的文档在何处显示。 

  `<a href="http://www.w3school.com.cn/" target="_blank">Visit W3School!</a>`

2. 通过使用 `name` 属性 - 创建文档内的书签
    `<a href="#000">第一章</a>`
    `<a name="000">第一章在这里</a>`
    **在HTML中点击href那个一句话，就能连接到name文章中的位置**

3. 也可以在在其他页面中创建指向该锚的链接
    `<a href="http://www.w3school.com.cn/html/html_links.asp#000">第一章</a>`
    **就是在链接的后面加上`#`以及锚的名称**
### 图像
1. 插入图像 
`<img src="url" />`
2. 替换文本属性（Alt）
`<img src="boat.gif" alt="Big Boat">`
> 在浏览器无法载入图像时，替换文本属性告诉读者她们失去的信息。此时，浏览器将显示这个替代性的文本而不是图像。
3. 背景图片
`<body background="/i/eg_background.jpg">`
> gif 和 jpg 文件均可用作 HTML 背景。如果图像小于页面，图像会进行重复。
4. 图像对其方式
`<img src="/i/eg_cute.gif"align="bottom">`
> `left`表示浮于左侧`right`表示浮于右侧
5. 图像作为链接 
    `<a href="/example/html/lastpage.html">
    <img border="0" src="/i/eg_buttonnext.gif" />
    </a>`
### 列表
1. 无序列表
```html
<ul>
  <li>咖啡</li>
  <li>茶</li>
  <li>牛奶</li>
</ul>
```

2. 有序列表
```html
<ol>
  <li>咖啡</li>
  <li>牛奶</li>
  <li>茶</li>
</ol>

<ol start="50">
  <li>咖啡</li>
  <li>牛奶</li>
  <li>茶</li>
</ol>
```



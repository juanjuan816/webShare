# JavaScript简介

JavaScript 是一中Web编程语言，能够给网页添加交互行为。有了JavaScript，能够使网页与用户互动，响应有趣的事件，从网上收集数据并将其用于网页中等。

1.如何将JavaScript代码加入网页

- 内部写

```
<html>
<body>

<script type="text/javascript">
	document.write("<h1>这是标题</h1>");
</script>

</body>
</html>

```
- 外部引入

```
<html>
<head>
</head>
<body>

<script src="/js/example_externaljs.js">
</script>

<p>
实际的脚本位于名为 "xxx.js" 的外部脚本中。
</p>

</body>
</html>

```
注：一般来说，为了网页加载性能，通常将CSS文件放在头部，JavaScript文件放在尾部。
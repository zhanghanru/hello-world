# hello-world
第一个库
<html>

	<head>
		<!--<meta charset="utf-8"/>-->
		<title>超链接</title>
	</head>
		<body>

	<!--
		使用超链接可以让我们从一个页面跳转到另一个页面
		使用a标签来创建一个超链接
		属性：
		  href:指向连接跳转的目标地址，可以写一个相对路径，也可以写一个完整的地址
		target:可以用来指定打开链接的位置，可选择的值
			_self  表示在当前窗口打开，（默认值）
			_blank 表示在一个新的窗口中打开超链接
		可以设置一个内联框架的name值，使链接在指定的内联框架中打开。
		例如：
		<iframe src="test.html" name="tom"><iframe>
	-->
		<center>
			<p>标签中的内容会默认在页面中居中显示</p>
		</center>
		<a href="www.baidu.com">我是一个超链接</a><br>
		
		<a href="test.html" target="tom">我是一个超链接</a><br/><br/>
		<iframe src="test.html" name="tom"></iframe>
		<center>
			<p>标签中的内容会默认在页面中居中显示</p>
		</center>
		</body>
</html>

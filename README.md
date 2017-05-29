# zone
HTML的结构
HTML的基本结构:
<!DOCTYPE html>
<!--引用dtd规范,HTML5是妥协的标准,不需引用-->
<html>
<根元素标签,成对出现,代表HTML文档的开始和结束>
	<head>
<!--头部,可以放很多供浏览器识别和使用的部件-->
		<meta http-equiv="Content-Type" content="text/html;charset=gb2312" />
		<title>我的第一个网页</title>
	</head>
	<body>
<!--身体,放页面文件的主体-->
		<p>海通网校</p>
	</body>
</html>
head标签内的常用元素
<>title>定义文档标题
<script>用于包含JavaScript脚本
<link>链接外部CSS样式文件
<style>用于定义内部css样式
<meta>用于HTML页面的元数据
title标签:提供给搜索引擎识别和使用的标签(放关键字,核心内容)
格式:<head>
		<title>海通网校-一个知名的培训点</title>
	</head>
meta标签:用于定义页面的元信息,也就是一些键值对,主要有三个属性:
           http-equiv:指定元信息的名称,具有特殊意义,他可以向浏览器传回一些有用的信息,帮助浏览器正确的处理内容
            name:指定元信息名称,该名称可随意指定
            content:指定元信息的值
例如:<head>
                <meta http-equiv="Content-Type"   
                      content="text/html;charset=gbk" />                       
        </head>
         <head>
                 <meta name="author" content="饭饭" />
                 <meta name="keyword" content="Java论坛,Android论坛,lsd论坛" />
                    <meta name="description" content="............" />
           </head>
其中的keyword和description也能被搜索引擎识别和使用,也放置一些关键内容
建立一个HTML文件:index.html
<!doctype html>
<html>
	<head>
	<title>海同科技是上海最大的嵌入式开发培训机构</title>
		<meta http-equiv="Content-Type" content="text/html;charset=gbk2312" />
		<meta name="keywords" content="java培训,Android培训,LSD培训" />
		<meta name="description" content="海通科技是一家集Java培训和Android培训的一家培训机构"/>
	</head>
	<body>
	</body>
</html>

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title></title>
	<style type="text/css">
		*{
			padding:0px;
			margin: 0px;
		}
		.top{
			height: 50px;
			width: auto;
			background-color: #C0C0C0;
			margin: 0px auto;
		}
		.right{
			position:absolute;
			top: 50px;
			right: 0px;
			width: 70px;
			height: 100%;
			background-color: #00AAAA;
		}
		.foot{
			width: 100%;
			height: 50px;
			position: fixed;
			bottom: 0px;
			background-color: #C0C0C0;
			text-align: center;
			line-height: 50px;
			overflow: hidden;
		}
		.nav{
			text-align: center;
		}
		.nav ul{
			display: inline-block;
		}
		.nav li{
			float: left;
			margin-top: 12.5px;
		}
		.nav li+li{
			margin-left: 20px;
		}
		a{text-decoration: none;}
		li{
			list-style-type: none;
		}
	</style>
</head>
<body>
	<div class="content">
		<div class="top">
			<div class="nav">
			<ul>
				<li><a href="#">主页</a></li>
				<li><a href="#">内容</a></li>
				<li><a href="#">内容</a></li>
				<li><a href="#">内容</a></li>
				<li><a href="#">内容</a></li>
			</ul>
			</div>
			
		</div>
		<div class="right">
			
		</div>
		<div class="foot">
			<p class="banquan">版权信息</p>
		</div>
	</div>

</body>
</html>

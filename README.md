<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title></title>
		<style>
			*{
				margin: 0;
				padding: 0;
			}
			body{
				font-size: 14px;
				font-family: "宋体";
				background-image: url(img/10.jpg);
				background-repeat: no-repeat;
				background-size: 100%;
			}
			.heading{
				width: 980px;
				height: 100px;
				text-align: center;
				line-height: 50px;
				/*margin: 100px auto;*/
				position: absolute;
				left: 200px;
				top: 80px;
				color: yellow;
				font-size: 30px;
			}
			h1,.content{
				color: yellow;
			}
			.content{
				width: 980px;
				height: 200px;
				padding: 20px;
				margin: 0 auto;;
				position: absolute;
				left: 1200px;
				top: 300px;
				text-align: center;	
			}
		</style>
	</head>
	<body>
		<div class="heading">
			<h1>欢迎来到温温奶茶店</h1>
		</div>
		<div class="content">
		<h1>输入您的奶茶</h1>
		口味：<input type="text" style="width: 200px;height: 30px;" /><br /><br />
		大小：<input type="text" style="width: 200px;height: 30px;" /><br /><br />
		<!--验证码：<input type="text"style="width: 200px;height: 30px;" /><br /><br />-->
		<a href="store.html"><input type="button" value="查询" style="width: 70px;height: 30px;background: yellow;"/></a>
		<input type="button" value="重填" style="width: 70px;height: 30px;background: yellow;"/>
		</div>
	</body>
</html>

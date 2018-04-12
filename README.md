# new-web-
web前段构造
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title>闲置网</title>
	<style type="text/css">
		body{
		margin:0px;
		background-color:#fff;
	      }
	    .bubble{
	    	width:1360px;
	    	height:300px;
	    	background-color:burlywood;
	    	margin:10px auto 100px auto 0;
	    	display:flex;
	    	justify-content:;
	    	align-items:center;
	    	filter:blur(100px) contrast(200px)
	          }
	        .abc1, .abc2, .abc3 {
	        	width: 100px;
	        	height: 100px;
	        	border-radius: 50%;	
	        }  
	        .abc3{
	        	background-color: #675408;
	        }
	        .abc2{
	        	animation:move 2s infinite alternate ease-in-out;
	        	background-color: #700000;
	        }
	        	.abc1{margin-left:430px;
	        	animation:move 2s infinite alternate ease-in-out;
	        	background-color: #065099;
	        }
	      
	         @keyframes move{	
	        	from{
	        		box-shadow: 100px 100px 0px #675408;
	        	}
	        	to{
	        		box-shadow: 100px -100px 0px #065099;
	        	}
	        }
	</style>
	</head> 
	<body>
		<center><b><i>欢迎访问闲置网!</i></b></center>
		<div class="bubble" align="center">
			<div class="abc1"><br />
				<font size="9" face="楷体">闲</font>
			</div>
			&nbsp; &nbsp; &nbsp;&nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp;
			&nbsp; &nbsp; 
			<div class="abc2"><br />
				<font size="9" face="楷体">置</font>
			</div>
			&nbsp; &nbsp; &nbsp;&nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp;
			&nbsp; &nbsp; 
			<div class="abc3"><br />
				<font size="9" face="楷体">网</font>
			</div> <br />
		</div><br /><br />
		<form action="">
		&nbsp;&nbsp;&nbsp;&nbsp;用户名：<input type="text" /><br /><br />
		&nbsp;&nbsp;&nbsp;&nbsp;密码：<input type="password" /><br /><br />&nbsp;&nbsp;
		&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<input type="submit" id="" name="log in" value="登录" />&nbsp;&nbsp;
		<input type="reset" id=""  name="reset" value="重置" />&nbsp;&nbsp;
		<input type="submit" id="" name="register" value="注册" />
		</form>
		
	</body>
</html>

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
	        	background-color: #222222;
	        }
	        .abc2{
	        	animation:move 2s infinite alternate ease-in-out;
	        	background-color: #700000;
	        }
	        	.abc1{margin-left:430px;
	        	animation:move 2s infinite alternate ease-in-out;
	        	background-color: #fff;
	        }
	      
	         @keyframes move{	
	        	from{
	        		box-shadow: 100px 100px 0px #065099;
	        	}
	        	to{
	        		box-shadow: 100px -100px 0px #675408;
	        	}
	        	
	        	pop()	
	        }
	</style>
	</head> 
	<body>
		hj
		<div class="bubble" align="center">
			<div class="abc1">
				<br /><br />
				 <b>闲</b>  
			</div>
			&nbsp; &nbsp; &nbsp;&nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp;
			&nbsp; &nbsp; 
			<div class="abc2">
				<br /><br />
				 <b>置</b>
			</div>
			&nbsp; &nbsp; &nbsp;&nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp;
			&nbsp; &nbsp; 
			<div class="abc3">
				<br /><br />
				<b size="677">网</b>
			</div>
			 <br />
		</div>
	</body>
</html>

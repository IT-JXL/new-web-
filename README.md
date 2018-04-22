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
		<h1><font size="">网站一级标题</font> </h1>
		<ul type="square">
			<li><a href="http://www.baidu.com">导航链接一</a></li>
			<li><a href="http://www.baidu.com">导航链接二</a></li>
			<li><a href="http://www.baidu.com">导航链接三</a></li>
			<li><a href="http://www.baidu.com">导航链接四</a></li>
		</ul>
		<h2>文章一级标题</h2>
		<h3>文章二级标题</h3>
		<p>文章作者&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;文章发表时间</p>
	    <p>这是一个很长很长的段落这是一个很长很长的段落这是一个很长很长的段落这是一个很长很长的段落这是一个很长很长的段落
	    	<p>换行了</p>这是一个很长很长的段落这是一个很长很长的段落<a href="http://www.baidu.com">这里有个链接，链接到baidu</a>这是一个很长很长的段落这是一个很长很长的段落这是一个很长很长的段落<strong>这里有个粗体字</strong>这是一个很长很长的段落这是一个很长很长的段落</p>
	    <h2>另一个文章一级标题</h2>
	    <h3>文章二级标题</h3>
		<p>文章作者&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;文章发表时间</p>
	    <h2>图片</h2>	
	    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;好看的图片</p>
	    <img src="aaa.jpg" alt="" />
	     <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;好看的图片</p>
	    <img src="aaa.jpg" alt="" />
		<h2>最后一个文章一级标题</h2>
		<h3>文章二级标题</h3>
		<p>文章作者&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;文章发表时间</p>
		<ol type="1">
			<li>排名一</li>
			<li>排名二</li>
			<li>排名三</li>
		</ol>
		<p>下面是一张表格，给表格加一个border="1"好让你看出是一个表格</p>
		<table border="1">
			<th>表头</th>
			<th>表头</th>
			<tr>
				<td>表内容单元格</td>
				<td>表内容单元格</td>
				<td><a href="http://www.baidu.com">操作</a></td>
			</tr>
			<tr>
				<td>表内容单元格</td>
				<td>表内容单元格</td>
				<td><a href="http://www.baidu.com">操作</a></td>
			</tr>
			<tr>
				<td>表内容单元格</td>
				<td>表内容单元格</td>
				<td><a href="http://www.baidu.com">操作</a></td>
			</tr>
			<tr>
				<td>总计</td>
				<td>1000</td>
			</tr>
		</table>
		<p><font size="5">这里以后是一个侧栏，这是侧栏的标题</font></p>
		<p><font size="4">侧栏注册窗口标题</font></p>
		请输入邮箱地址<input type="text" />
		<br />
		<p><b><i>邮箱地址请按格式要求输入</i></b></i></p>
        <p>请输入密码<input type="password" /></p>
        <p>请重复输入密码<input type="password" /></p>
        <p><b><i>密码请为6-16位英文或数字</i></b></i></p>
                            性别:&nbsp;&nbsp;<input type="radio" id="" name="sex" value="男" checked="checked"/>男
                        <input type="radio" id="" name="sex" value="女" />女
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                            城市：&nbsp;&nbsp;<select name="fruit">
                            	<option value="hongkong">香港</option>
                            	<option value="taiwan">台湾</option>
                            </select><br />
                            爱好：&nbsp;&nbsp;<input type="checkbox" name="habit"/>运动         
                           <input type="checkbox" name="habit"/>艺术
                           <input type="checkbox" name="habit" checked="checked"/>科学<br />
                           个人描述：<textarea name="" id="10" cols="20" rows="2" placeholder="这是一个多行描述框，输入你的个人描述"></textarea><br />
        <input type="submit" name="" id="" value="确认提交" />
        <input type="reset" name="" id="" value="重置" />

	</body>
</html>

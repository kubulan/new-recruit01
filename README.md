<!DOCTYPE HTML>
<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
<title>新生填报</title>
</head>
<body>
<form  method="post" action="save.php">
姓名：
<input type="text" name="myName" />
<br />
<label>性别:</label>
<label>男</label>
<input type="radio" value="1"  name="gender" />
<label>女</label>
<input type="radio" value="2"  name="gender" />
<br />
<label>意向部门:</label>
<select>
<option value="综合办公室">综合办公室</option>
<option value="公安策划部">公安策划部</option>
<option value="视觉设计部">视觉设计部</option>
<option value="技术开发部">技术开发部</option>
<option value="综合媒体集团">综合媒体集团</option>
<option value="新闻集团">新闻集团</option>
<option value="视频集团">视频集团</option>
</select>
<br />
学院专业班级:
<input type="text" name="class" />
<br />
<label>个人简介：</label>
<textarea rows="10" cols="50">在这里输入内容...</textarea>
<br />
<label for="email">输入你的邮箱地址</label>
<input type="email" id="email" placeholder="Enter email"><br />
<br />
<input type="submit" value="提交" name="submitBtn" />


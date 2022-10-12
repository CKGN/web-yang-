<!DOCTYPE html>
<html>
	<head>
		<meta charst="utf-8">
		<title></title>
	</head>
	<body>
		<table border="1">
			<tr>
				<th colspan="2">
					<b>信息统计表</b>
				</th>
			</tr>
			<tr>
				<td>姓名:</td>
				<td><input type="text"name="username"></td>
			</tr>
			<tr>
				<td>年龄：</td>
				<td><input type="text"name="age"></td>
			</tr>
			<tr>
				<td>性别：</td>
				<td>
					<input type="radio"name="sex"value="男"checked>男
					<input type="radio"name="sex"value="女">女
				</td>
			</tr>
			<tr>
				<td>爱好:</td>
				<td>
					<input type="checkbox"name="hobby"value=1>羽毛球
					<input type="checkbox"name="hobby"value=2>乒乓球
					<input type="checkbox"name="hobby"value=3>篮球
					<input type="checkbox"name="hobby"value=4>小说
					<input type="checkbox"name="hobby"value=5>听歌
				</td>
			</tr>
			<tr>
				<td>学历：</td>
				<td>
					<select name="degree">
						<option value="0">--请选择--</option>
						<option value="1">专科</option>
						<option value="2">本科</option>
						<option value="3">研究生</option>
						<option value="4">硕士</option>
						<option value="5">博士及以上</option>
					</select>
				</td>
			</tr>
			<tr>
				<td>自我介绍：</td>
				<td>
					<textarea name="comment"rows="7"cols="30"></textarea>
				</td>
			</tr>
			<tr>
				<td colspan="2"align=center>
					<button>提交</button> <button>重置</button> <button>返回</button>
				</td>
			</tr>
		</table>
	</body>
</html>

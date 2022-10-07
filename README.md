
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title>注册页面</title>
	</head>
	<body>
		<table width="520" height="450">
			<tr>
				<td>姓名：</td>
				<td>
					<input type="text" name="name" value="请输入你的姓名..." />
				</td>
			</tr>
			<tr>
				<td>年龄：</td>
				<td>
					<input type="text" name="age" value="请输入你的年龄..." />
				</td>
			</tr>
			<tr>
				<td>性别：</td>
				<td>
					<input type="radio" name="sex" id="boy" />
					<label for="boy"><img src="man.png" width="15" height="15" />男</label>
					<input type="radio" name="sex" id="girl" />
					<label for="girl"><img src="girl.png" width="15" height="15" />女</label>
				</td>
			</tr>
			<tr>
				<td>生日：</td>
				<td>
					<select>
						<option selected>--请选择年份--</option>
						<option>2002</option>
						<option>2003</option>
						<option>2004</option>
					</select>
					<select>
						<option selected>--请选择月份--</option>
						<option>1月</option>
						<option>2月</option>
						<option>3月</option>
						<option>4月</option>
						<option>5月</option>
						<option>6月</option>
						<option>7月</option>
						<option>8月</option>
						<option>9月</option>
						<option>10月</option>
						<option>11月</option>
						<option>12月</option>
					</select>
					<select>
						<option selected>--请选择日--</option>
						<option>1日</option>
						<option>2日</option>
						<option>3日</option>
						<option>4日</option>
						<option>5日</option>
						<option>6日</option>
						<option>7日</option>
						<option>8日</option>
						<option>9日</option>
					</select>
				</td>
			</tr>
			<tr>
				<td>爱好：</td>
				<td>
					<input type="checkbox" name="like" id="a" /><label for="a">阅读</label>
					<input type="checkbox" name="like" id="b" /><label for="b">跑步</label>
					<input type="checkbox" name="like" id="c" /><label for="c">游泳</label>
					<input type="checkbox" name="like" id="d" /><label for="d">听歌</label>
				</td>
			</tr>
			<tr>
				<td>个人介绍：</td>
			</tr>
			<tr>
				<td colspan="2"><textarea rows="6" cols="50">请输入你的个人介绍....</textarea></td>
			</tr>
			<tr>
				<td align="center" colspan="2"><input type="checkbox" name="agree" id="f" checked /><label
						for="f">我同意信息录入</label></td>
			</tr>
			<tr>
				<td align="center" colspan="2">
					<input type="submit" value="立即注册" />
					<input type="reset" value="重新输入" />
				</td>
			</tr>
		</table>
	</body>
</html>

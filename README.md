
<html>
<body>
<table border="0">
	<tr>
		<td>User ID</td>
		<td><input id="v1"></td>
	</tr>
	<tr>
		<td>Name</td>
		<td><input id="v2"></td>
	</tr>
	<tr>
		<td>Password</td>
		<td><input id="v3"></td>
	</tr>
	<tr>
		<td>Email ID</td>
		<td><input id="v4"></td>
	</tr>
	<tr>
		<td>Contact</td>
		<td><input id="v5"></td>
	</tr>
	<tr>
		<td>Address</td>
		<td><input id="v6"></td>
	</tr>
	<tr>
		<td>Date of birth</td>
		<td><input id="v7"></td>
	</tr><tr>
		<td>country</td>
		<td><select id="v8">
              <option>India</option>
		    </select>
		</td>
	</tr>
	<tr>
		<td></td>
		<td><input type="button" value="Register" onclick="xyz()"></td>
	</tr>
</table><br>
<p id=p1></p>
<p id=p2></p>
<p id=p3></p>
<p id=p4></p>
<p id=p5></p>
<p id=p6></p>
<p id=p7></p>
<p id=p8></p>

<script>
	function xyz() {
		
		a=v1.value;
		b=v2.value;
		c=v3.value;
		d=v4.value;
		e=v5.value;
		f=v6.value;
		g=v7.value;
		h=v8.value;

		output="<table border='1'>"
		output+="<tr><td>User ID<td>"+a
		output+="<tr><td>Name:<td>"+b
		output+="<tr><td>Password<td>"+c
		output+="<tr><td>Email ID:<td>"+d
		output+="<tr><td>Contact<td>"+e
		output+="<tr><td>Address:<td>"+f
		output+="<tr><td>Date of birth:<td>"+g
		output+="<tr><td>country:<td>"+h

		p1.innerHTML=output;
	}
</script>
</body>
</html>

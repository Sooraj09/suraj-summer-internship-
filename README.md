

<body>
                   <h1>Students Marks REcord</h1>
	<P>Physics     <input id="M1"></P>
	<P>Chemistry   <input id="M2"></P>
	<P>Maths       <input id="M3"></P>
	<P>English     <input id="M4"></P>
	<P>PE          <input id="M5"></P>
	<input type="button" value="add and average" onclick="xyz()" id="t6"><br><br>
	<output id="total"></output><br>
                   <output id="avg"></output>
	<script>
		function xyz()
		{
			a=parseInt(M1.value);
			b=parseInt(M2.value);
			c=parseInt(M3.value);
			d=parseInt(M4.value);
			e=parseInt(M5.value);
			f=a+b+c+d+e;
                                                         g=f/5;
			total.value='Total :' + f
                                                         avg.value='average :' + g
		}
	</script>
</body>

<html>
<body>
      <table border="1">
            <tr>
	<td colspan="4"><input id="input1" ></input></td>
           </tr>
           <tr>
                  <td colspan="4"><input id="input2" ></input></td>
           <tr>
           <tr>
                  <td><input type="button" value="+" onclick="add()" ></input></td>
                  <td><input type="button" value="-" onclick="sub()"></input></td>
                  <td><input type="button" value="*" onclick="mul()"></input></td>
                  <td><input type="button" value="/" onclick="div()"></input></td>
           </tr>
</table>
<p id="para"></p>
</body>

<script>{
    function add() {
        a_1=parseInt(input1.value);
        b_1=parseInt(input2.value);
        c_1=a_1+b_1;
        para.innerHTML="sum: " +c_1;}

       function sub() {
        a_2=parseInt(input1.value);
        b_2=parseInt(input2.value);
        c_2=a_2-b_2;
        para.innerHTML="substraction: " +c_2;}

        function mul() {
        a_3=parseInt(input1.value);
        b_3=parseInt(input2.value);
        c_3=a_3*b_3;
        para.innerHTML="multiplication: " +c_3;}
 
        function div() {
        a_4=parseInt(input1.value);
        b_4=parseInt(input2.value);
        c_4=a_4/b_4;
        para.innerHTML="division: " +c_4;}
}
</script>

</html>

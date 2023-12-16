# Apps-cool
<html>
<head>
<style>
b1 {
width:auto;
height:auto;
background-color:red;

}
#id1{
width:110px;
border:2px solid black;
}
</style>
</head>
<body align="center">
<div class="formstyle">
<form name="form1">
<input type="text" id="id1" name="calculator">
<hr width="110px" height="2px" color="black" >
<input type="button" name="b1" value="1" onclick="form1.calculator.value+=1">
<input type="button" name="b2" value="2" onclick="form1.calculator.value+=2">
<input type="button" name="b3" value="3" onclick="form1.calculator.value+=3">
<input type="button" name="b4" value="4" onclick="form1.calculator.value+=4">
<br>
<input type="button" name="b5" value="5" onclick="form1.calculator.value+=5">
<input type="button" name="b6" value="6" onclick="form1.calculator.value+=6">
<input type="button" name="b7" value="7" onclick="form1.calculator.value+=7">
<input type="button" name="b8" value="8" onclick="form1.calculator.value+=8">
<br>
<input type="button" name="b9" value="9" onclick="form1.calculator.value+=9">
<input type="button" name="b10" value="0" onclick="form1.calculator.value+=0">
<input type="button" name="b11" value="/" onclick="form1.calculator.value+='/'">
<input type="button" name="b12" value="*" onclick="form1.calculator.value+='*'">
<br>
<input type="button" name="b17" value="." onclick="form1.calculator.value+='.'">
<input type="button" name="b13" value="+" onclick="form1.calculator.value+='+'">
<input type="button" name="b15" value="=" onclick="form1.calculator.value=eval(form1.calculator.value)">
<br>
<input type="reset" id="id1" name="b16" value="reset" onclick="form1.calculator.value=''">
</form>
</div>
</body>
</html>

# amazing-calculator
<html>
<head>
<center>
<script type="text/javascript">
function displynum(n1)
{
jamescalcuform.txt1.value=jamescalcuform.txt1.value+n1;
}
</script>
</head>
<body>

<form name=jamescalcuform>
<input type=text name=txt1 style="text-align:right" size="10"><br>
<input type=button name=btn9 value=9 onclick="displynum(btn9.value)">
<input type=button name=btn8 value=8 onclick="displynum(btn8.value)">
<input type=button name=btn7 value=7 onclick="displynum(btn7.value)">
<input type=button name=btnadd value=+ onclick="displynum(btnadd.value)"><br>
<input type=button name=btn6 value=6 onclick="displynum(btn6.value)">
<input type=button name=btn5 value=5 onclick="displynum(btn5.value)">
<input type=button name=btn4 value=4 onclick="displynum(btn4.value)">
<input type=button name=btnsubb value=- onclick="displynum(btnsubb.value)"><br>
<input type=button name=btn3 value=3 onclick="displynum(btn3.value)">
<input type=button name=btn2 value=2 onclick="displynum(btn2.value)">
<input type=button name=btn1 value=1 onclick="displynum(btn1.value)">
<input type=button name=btnmul value=* onclick="displynum(btnmul.value)"><br>
<input type=button name=btn0 value=0 onclick="displynum(btn0.value)">
<input type=button name=btnpot value=. onclick="displynum(btnpot.value)">
<input type=button name=btneql value== onclick="txt1.value=eval(txt1.value)">
<input type=button name=btndiv value=/ onclick="displynum(btndiv.value)">
</body>
</center>
</html>

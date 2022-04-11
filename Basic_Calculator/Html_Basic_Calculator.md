```html
<!DOCTYPE html>
<html>
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1">
 <title>Basic Calculator</title>
 <link rel="stylesheet" type="text/css" href="Calc.css">
</head>
<body>

 <h1>Simple Calculator</h1>
 
 <form id="calcform" name="calc">
 
 <input name="display" style="width:490px; height:100px; text-align:center; background-color:#328da8">
 <input type="button" value="C" onclick="calc.display.value=' '" style="background-color:#ededd3;"></br> 
 <input type="button" value="7" onclick="calc.display.value+='7'">
 <input type="button" value="8" onclick="calc.display.value+='8'">
 <input type="button" value="9" onclick="calc.display.value+='9'">
 <input type="button" value="/" onclick="calc.display.value+='/'" style="background-color:#32a86d;"></br>
 <input type="button" value="4" onclick="calc.display.value+='4'">
 <input type="button" value="5" onclick="calc.display.value+='5'">
 <input type="button" value="6" onclick="calc.display.value+='6'">
 <input type="button" value="*" onclick="calc.display.value+='*'" style="background-color:#8e32a8"></br>
 <input type="button" value="1" onclick="calc.display.value+='1'">
 <input type="button" value="2" onclick="calc.display.value+='2'">
 <input type="button" value="3" onclick="calc.display.value+='3'">
 <input type="button" value="-" onclick="calc.display.value+='-'" style="background-color:#a89432;"></br>
 <input type="button" value="." onclick="calc.display.value+='.'">
 <input type="button" value="0" onclick="calc.display.value+='0'">
 <input type="button" value="=" onclick="calc.display.value=eval(calc.display.value)">
 <input type="button" value="+" onclick="calc.display.value+='+'" style="background-color:#a8325d;">

</form>

</body>

</html>
```

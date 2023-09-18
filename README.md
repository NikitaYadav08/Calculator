<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css"
    <title>calculator</title>
</head>
<body>
    <div class="wrap">
        <form name ="calcy">
            <input type="text" name="display" class="display"><br>
            <input type="button" class="button" value="C" onclick="calcy.display.value=''" id="del">
            <input type="button" class="button" value="/" onclick="calcy.display.value+='/'">
            <input type="button" class="button" value="*" onclick="calcy.display.value+='*'">
            <input type="button" class="button" value="<-" onclick="calcy.display.value= calcy.display.value.slice(0,-1)"><br>

            <input type="button" class="button" value="7" onclick="calcy.display.value+='7'">
            <input type="button" class="button" value="8" onclick="calcy.display.value+='8'">
            <input type="button" class="button" value="9" onclick="calcy.display.value+='9'">
            <input type="button" class="button" value="-" onclick="calcy.display.value+='-'"><br>

            <input type="button" class="button" value="4" onclick="calcy.display.value+='4'">
            <input type="button" class="button" value="5" onclick="calcy.display.value+='5'">
            <input type="button" class="button" value="6" onclick="calcy.display.value+='6'">
            <input type="button" class="button" value="+" onclick="calcy.display.value+='+'"><br>
        
            <input type="button" class="button" value="1" onclick="calcy.display.value+='1'">
            <input type="button" class="button" value="2" onclick="calcy.display.value+='2'">
            <input type="button" class="button" value="3" onclick="calcy.display.value+='3'">
            <input type="button" class="button" value="%" onclick="calcy.display.value+='%'"><br>

            <input type="button" class="button" value="." onclick="calcy.display.value+='.'">
            <input type="button" class="button" value="0" onclick="calcy.display.value+='0'">
            <input type="button" class="button" value="=" onclick="calcy.display.value= eval(calcy.display.value)">

    </div>
</body>
</html>

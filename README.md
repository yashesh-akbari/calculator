<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>calculator project</title>
    <!--This is DuckDuckGo brower calculator made by me -->
</head>
<body>
    <table border="5" width="250" height="300" align="center">
        <h1 align="center">calculator</h1>
        <tr>
            <!--display-->    
            <th id="display" colspan="4" align="right"></th>       
        </tr>
        <tr>
            <th align="center" onclick="enter_num='0';
            document.querySelector('#display').innerHTML = enter_num;" colspan="2">C</th>
            <th align="center"  onclick="enter_num=enter_num+'%';
            document.querySelector('#display').innerHTML = enter_num;"
            Style="background-color:lightgray"
            >%</th>
            <th align="center"  onclick="enter_num=enter_num+'/';
            document.querySelector('#display').innerHTML = enter_num;"
            style="background-color: yellow;">/</th>
        </tr>
        <tr>
            <th align="center" onclick="enter_num=enter_num+'7';
            document.querySelector('#display').innerHTML = enter_num;">7</th>
            <th align="center" onclick="enter_num=enter_num+'8';
            document.querySelector('#display').innerHTML = enter_num;">8</th>
            <th align="center" onclick="enter_num=enter_num+'9';
            document.querySelector('#display').innerHTML = enter_num;">9</th>
            <th align="center"  onclick="enter_num=enter_num+'*';
            document.querySelector('#display').innerHTML = enter_num;"
            style="background-color: yellow;">x</th>
        </tr>
        <tr>
            <th align="center" onclick="enter_num=enter_num+'4';
            document.querySelector('#display').innerHTML = enter_num;">4</th>
            <th align="center" onclick="enter_num=enter_num+'5';
            document.querySelector('#display').innerHTML = enter_num;">5</th>
            <th align="center" onclick="enter_num=enter_num+'6';
            document.querySelector('#display').innerHTML = enter_num;">6</th>
            <th align="center"  onclick="enter_num=enter_num+'-';
            document.querySelector('#display').innerHTML = enter_num;"
            style="background-color: yellow;">-</th>
        </tr>
        <tr>
            <th align="center" onclick="enter_num=enter_num+ '1';
            document.querySelector('#display').innerHTML = enter_num;">1</th>
            <th align="center" onclick="enter_num=enter_num+'2';
            document.querySelector('#display').innerHTML = enter_num;">2</th>
            <th align="center" onclick="enter_num=enter_num+'3';
            document.querySelector('#display').innerHTML = enter_num;">3</th>
            <th align="center"  onclick="enter_num=enter_num+'+';
            document.querySelector('#display').innerHTML = enter_num;"
            style="background-color: yellow;">+</th>
        </tr>
        <tr>
            <th align="center" onclick="enter_num=enter_num +'0';
            document.querySelector('#display').innerHTML = enter_num;"  colspan="2"; >0</th>
            <th align="center" onclick="enter_num=enter_num+'.';
            document.querySelector('#display').innerHTML = enter_num;">.</th>
            <th align="center" 
            onclick="
            let result = eval(enter_num);
            enter_num = result;
            document.querySelector('#display').innerHTML = enter_num;" style="background-color: yellow;">=</th>
        </tr>
    </table>
    <script>
        let enter_num = '0';
        document.querySelector('#display').innerHTML = enter_num;
    </script>
</body>
</html>

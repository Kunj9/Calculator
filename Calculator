<html>
    <head>
        <title>Calculator</title>
        <link rel="icon" type="image/png" href="IMAGES/hex.png" sizes="96x96" />
         <link rel="stylesheet" href="basic_calculator.css">
    </head>
    <body>
    <center><h1>Calculator</h1></center>
            <script>
                function calc() {
                    var num1 = parseInt(document.getElementById('num1').value); 
                    var num2 = parseInt(document.getElementById('num2').value);
                    var sign = document.getElementById('operators').value;
                    if (sign === '+'){
                       document.getElementById('result').value= num1+num2;
                    }
                    if (sign ==='-'){
                        document.getElementById('result').value= num1 - num2;
                    }
                    if (sign === '/'){
                        document.getElementById('result').value= num1 / num2;
                    } 
                    if (sign === 'X'){
                        document.getElementsById('result').value= num1 * num2;
                    }
                    if (sign === '%'){
                        document.getElementById('result').value= ((num1 / num2) * 100);
                    }
                }

            </script>
         <center><label>Number1</label>
            <input type="text" id="num1"/><br>

            <select id="operators">
                <option value="+">+</option>
                <option value="-">-</option>
                <option value="/">/</option>
                <option value="X">X</option>
                <option value="%">%</option>
            </select><br>
            
            <label>Number2</label>
            <input type="text" id="num2"/><br><br>
            
            <button onclick="calc();"> = </button>
            <input type="text" id="result"/>
        </center>
    </body>
</html>

# ELIGILIBITY-CALCULATOR
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Javascript</title>
    <script>
        function add() {
            let num1 = parseInt(document.getElementById('num1').value);
            let num2 = parseInt(document.getElementById('num2').value);
            let num3 = num1 + num2;
            myForm.sum3.value = num3;
        }

        function sub() {
            let num1 = parseInt(document.getElementById('num1').value);
            let num2 = parseInt(document.getElementById('num2').value);
            let num3 = num1 - num2;
            myForm.sum3.value = num3;
        }

        function mod() {
            let num1 = parseInt(document.getElementById('num1').value);
            let num2 = parseInt(document.getElementById('num2').value);
            let num3 = num1 % num2;
            myForm.sum3.value = num3;
        }

        function multi() {
            let num1 = parseInt(document.getElementById('num1').value);
            let num2 = parseInt(document.getElementById('num2').value);
            let num3 = num1 * num2;
            myForm.sum3.value = num3;
        }

        function reset() {
            document.getElementById('num1').reset();
            document.getElementById('num2').reset();
            document.getElementById('num3').reset();
        }
    </script>
	<style>
body{
background-color:pink;
}
</style>
</head>


<body>
    <fieldset>
        <div style=" border: 1px solid rgb(233,55, 54);text-align:center;">
        <div style=" border: 1px solid rgb(233,55, 54);text-align:center;">
            <h1 style="color:blue;"> ELIGILIBITY CALCULATOR</h1>
            <form id="myForm">
                <input type="number" id="num1" placeholder="Enter first no."><br><br><br>
                <input type="number" id="num2" placeholder="Enter second no."><br><br><br>
                <input type="number" id="sum3" placeholder="Result"><br><br><br><br>
                <input type="button" value="Add" onclick="add()"><br><br><br>
                <input type="button" value="Substract" onclick="sub()"><br><br><br>
                <input type="button" value="Modulus" onclick="mod()"><br><br><br>
                <input type="button" value="Multiply" onclick="multi()"><br><br><br>
                <input type="button" value="Reset" onclick="reset()"><br><br><br>
            </form>
        </div>
    </fieldset>
</body>

</html>

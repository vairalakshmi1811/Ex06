# Ex.06 JavaScript - Student Result
## DATE:01/04/2024
## AIM
  To write a program in JavaScript for displaying the result of a student.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to generate the result grade.

### STEP-3
  Using branching statements analyze the grade achieved.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
```
<html>
<head>
<script>
function grading() {
    var val1 = parseInt(document.getElementById("num1").value);
    var val2 = parseInt(document.getElementById("num2").value);
    var val3 = parseInt(document.getElementById("num3").value);
    var val4 = parseInt(document.getElementById("num4").value);
    var val5 = parseInt(document.getElementById("num5").value);

    var final = val1 + val2 + val3 + val4+ val5;
    document.getElementById("result").innerHTML = +final  + " / 500 ";
    
}

function average() {
    var val1 = parseInt(document.getElementById("num1").value);
    var val2 = parseInt(document.getElementById("num2").value);
    var val3 = parseInt(document.getElementById("num3").value);
    var val4 = parseInt(document.getElementById("num4").value);
    var val5 = parseInt(document.getElementById("num5").value);

    var final1 = val1 + val2 + val3 + val4+ val5; 
    var total = final1 / 5;
    document.getElementById("avrg").innerHTML = +total;
}
   
function system(){
    var val1 = parseInt(document.getElementById("num1").value);
    var val2 = parseInt(document.getElementById("num2").value);
    var val3 = parseInt(document.getElementById("num3").value);
    var val4 = parseInt(document.getElementById("num4").value);
    var val5 = parseInt(document.getElementById("num5").value);

    var final1 = val1 + val2 + val3 + val4+ val5; 
    var total = final1 / 5;
    document.getElementById("grad");
      if((total>=91)&&(total<=100))
{
    alert("O Grade");
}
else if((total>=81)&&(total<=90))
{
    alert("A+ Grade");
}
else if((total>=71)&&(total<=80))
{
    alert("A Grade");
}
else if((total>=61)&&(total<=70))
{
    alert("B+ Grade");
}
else if((total>=51)&&(total<=60))
{
    alert("B Grade");
}
else
{
    alert(" U Grade");
}
}
</script>
</head>
<body bgcolor="skyblue">
<center>
<form>
    <table>
    <tr>
            <td>student's name:</td>
            <td><input type="text"/></td>
    </tr>
    <tr>
            <td>register no:</td>
            <td><input type="number" /></td>
    </tr>
    
    <tr>
        <td>tamil</td>
        <td><input type="number" id="num1"/></td>
    <tr>
        <td>English</td>
        <td><input type="number" id="num2"></td>
    </tr>
    <tr>
        <td>maths</td>
        <td><input type="number" id="num3"></td>
    <tr>
        <td>science</td>
        <td><input type="number" id="num4"></td>
    <tr>
        <td>social</td>
        <td><input type="number" id="num5"></td>
    </tr>
<br>
</table>
</form>
<button onClick="grading()">Total</button>
    <p id="result"></p><br>
    <button onClick="average()">Average</button><br>
    <p id="avrg"></p><br>
    <button onClick="system()">Grade</button><br>
    <p id="grad"></p>

</center>
</body>
</html>
```
## OUTPUT
![Screenshot 2024-05-01 233242](https://github.com/vairalakshmi1811/Ex06/assets/165985148/cca21716-1f74-476d-b7bf-2542e6061f7d)
![Screenshot 2024-05-01 233257](https://github.com/vairalakshmi1811/Ex06/assets/165985148/69258d09-dc24-47d5-a197-d289a65a7d96)



## RESULT
  Student result using JavaScript is created successfully.

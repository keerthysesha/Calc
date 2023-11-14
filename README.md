# Ex.08 Design of a Standard Calculator
## Register Number: 212221040082
## Date: 14-11-2023

## AIM:
To design a web application for a standard calculator with minimum five operations.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for creating attractive colors.

### Step 4:
Write JavaScript program for implementing five different operations.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :

### Calculator.html:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>CALCULATOR</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width initial-scale=1.0">
        <link rel="stylesheet" href="calculators.css">
        <link rel="icon" href="budget.png">
    </head>
    <body>
        <div class= "formstyle">
            <form name = "form1">
              <h2>CALCULATOR</h2>
              <input id = "calc" type ="text" name = "answer"> <br> <br>
              <input type = "button" value = "C" onclick = "form1.answer.value = ' ' " id= "clear" >
              <input type="button" value="√" id="operator5" onclick="form1.answer.value = Math.sqrt(eval(form1.answer.value))">
              <input type="button" value="x²" id="operator6" onclick="form1.answer.value = Math.pow(form1.answer.value, 2)">
              <input type = "button" value = "/" id="operator1" onclick = "form1.answer.value += '/' ">
              <br> <br>
              <input type = "button" value = "1" onclick = "form1.answer.value += '1' ">
              <input type = "button" value = "2" onclick = "form1.answer.value += '2' ">
              <input type = "button" value = "3" onclick = "form1.answer.value += '3' ">
              <input type = "button" value = "+" id="operator2" onclick = "form1.answer.value += '+' ">
              <br> <br>
              <input type = "button" value = "4" onclick = "form1.answer.value += '4' ">
              <input type = "button" value = "5" onclick = "form1.answer.value += '5' ">
              <input type = "button" value = "6" onclick = "form1.answer.value += '6' ">
              <input type = "button" value = "-" id="operator3" onclick = "form1.answer.value += '-' ">
              <br> <br>
              <input type = "button" value = "7" onclick = "form1.answer.value += '7' ">
              <input type = "button" value = "8" onclick = "form1.answer.value += '8' ">
              <input type = "button" value = "9" onclick = "form1.answer.value += '9' ">
              <input type = "button" value = "*"  id="operator4"onclick = "form1.answer.value += '*' ">
              <br> <br>
              <input type = "button" value = "0" onclick = "form1.answer.value += '0' ">
              <input type = "button" value = "." onclick = "form1.answer.value += '.' ">
              <input type = "button" value = "=" onclick = "form1.answer.value = eval(form1.answer.value)"" id="equal">
              <br> <br>
            </form>
            </div>
    </body>
</html>
```
### Calculators.css:
```
 h2 {
	font-size: 50px;
    text-align: center;
    font-family: Arial, Helvetica, sans-serif;
    color: white;
    text-shadow: 2px 2px 4px #000000;
    margin-top: -5px;
    font-weight: bolder;
	}

#clear{
    width: 70px;
    height: 70px;
    border: none;
    border-radius: 10px;
    box-shadow:0 8px 8px rgba(0, 0, 0, .5);
    text-align: right;
    font-size: xx-large;
    text-align: center;
    margin-left: 18px;
    background-color: #46005f;
}

.formstyle
{
    width: 385px;
    height: 620px;
    margin-left: 580px;
    margin-right: 580px;
    padding: 10px;
    border-radius: 5px;
    margin-top: 50px;
    background-color: #ecdff5;
    box-shadow:20px 40px 40px rgba(0, 0, 0, .5);
}

input[type=button]{
    width: 70px;
    height: 70px;
    border: none;
    border-radius: 10px;
    box-shadow:0 8px 8px rgba(0, 0, 0, .5);
    text-align: right;
    font-size: xx-large;
    text-align: center;
    margin-left: 18px;
    background-color: blue;
    color: white;
    font-weight: bold;
}

#calc
{
    width:350px;
    height: 70px;
    border: none;
    border-radius: 20px;
    margin-top: -20px;
    box-shadow:0 5px 5px rgba(0, 0, 0, .5);
    text-align: right;
    font-size: xx-large;
    margin-left: 18px;
    font-weight: bolder;
}
#equal{
    width: 165px;
    border: none;
    border-radius: 10px;
    box-shadow:0 8px 8px rgba(0, 0, 0, .5);
    text-align: right;
    font-size: xx-large;
    text-align: center;
    margin-left: 18px;
    background-color: #46005f;
}
#operator1{
    background-color: cyan;
}
#operator2{
    background-color: cyan;
}
#operator3{
    background-color: cyan;
}
#operator4{
    background-color: cyan;
}
#operator5{
    background-color: cyan;
}
#operator6{
    background-color: cyan;
}
```

## OUTPUT:

![image](https://github.com/keerthysesha/Calc/assets/125575936/72b0748d-a041-4853-a4e2-95df73ad1dcd)




## RESULT:
The program for designing a standard calculator using HTML and CSS is executed successfully.


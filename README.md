# Calculator
A simple calculator using HTML,CSS,JavaScript
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css" integrity="sha384-xOolHFLEh07PJGoPkLv1IbcEPTNtaed2xpHsD9ESMhqIYd0nLMwNLD69Npy4HI+N" crossorigin="anonymous">

    <title>Utilities</title>
  </head>
  <style>
    li>a
    {
        color: white;
    }
.title {  
margin-bottom: 10px;  
padding: 5px 0;  
font-size: 40px;  
font-weight: bold;  
text-align: center;  
color: black;    
}  
input[type=button] {  
  width: 60px;  
  height: 60px;  
  float: left;  
  padding: 0;  
  margin: 5px;  
  box-sizing: border-box;  
  background: #1653cc;  
  border: none;  
  font-size: 30px;  
  line-height: 30px;  
  border-radius: 50%;  
  font-weight: 700;  
  color: black;  
  cursor: pointer;    
}  
input[type=text] {  
  width: 270px;  
  height: 60px;  
  float: left;  
  padding: 0;  
  box-sizing: border-box;  
  border: none;  
  background: none;  
  color: white;  
  text-align: right;  
  font-weight: 700;  
  font-size: 60px;  
  line-height: 60px;  
  margin: 0 25px;  
  }  
.calculator {   
  box-shadow: 0px 0px 0px 10px #666;  
  border: 5px solid black;  
  border-radius: 10px;  
}  
#display {  
  height: 40px;  
  text-align: right;  
  background-color: black;  
  border: 3px solid white;  
  font-size: 18px;  
  left: 2px;  
  top: 2px;  
  color: white;  
}  
.btnTop {  
  color: white;  
  background-color: white;  
  font-size: 14px;  
  margin: auto;
  width: 50px;  
  height: 25px;  
}     
     
   
  </style>
  <body style="background-image: url(./Backgrounds/maths\ back.jpg);">
   <form name="Calculator" class = "calculator" style="height: 1000px;"> 
    <div class = "title"  align="center">  
      Calculator 
    </div>   
<table border="2" align="center" cellpadding="15" cellspacing="12" bgcolor="white">  
<tr>  
<td>  
<input type="text" name="Input" Size="35" id="display">  
<br>  
</td>  
</tr>  
<tr>  
<td>  
<input type="button" name = "one" style="font-size:30px" value=" 1 " OnClick="Calculator.Input.value += '1'">  
<input type="button" name = "two" style = "font-size:30px" value=" 2 " OnCLick="Calculator.Input.value += '2'">  
<input type="button" name = "three" style="font-size:30px" value=" 3 " OnClick="Calculator.Input.value += '3'">  
<input type="button" name="add" class ="btnTop" style="font-size:30px" value=" + " OnClick="Calculator.Input.value += ' + '">  
<br>  
<input type="button" name = "four" style="font-size:30px" value=" 4 " OnClick="Calculator.Input.value += '4'">  
<input type="button" name = "five" style="font-size:30px" value=" 5 " OnCLick="Calculator.Input.value += '5'">  
<input type="button" name = "six" style="font-size:30px" value=" 6 " OnClick="Calculator.Input.value += '6'">  
<input type="button" name = "minus" style="font-size:30px" value=" - " OnClick="Calculator.Input.value += ' - '">  
<br>  
<input type="button" name = "seven" style="font-size:30px" value=" 7 " OnClick="Calculator.Input.value += '7'">  
<input type="button" name = "eight" style="font-size:30px" value=" 8 " OnCLick="Calculator.Input.value += '8'">  
<input type="button" name = "nine" style="font-size:30px" value=" 9 " OnClick="Calculator.Input.value += '9'">  
<input type="button" name = "mul" style="font-size:30px" value=" * "   
OnClick="Calculator.Input.value += ' * '">  
<br>  
<input type="button" name = "clear" style="font-size:30px" value=" c " OnClick="Calculator.Input.value = ''">  
<input type="button" name="zero" style="font-size:30px" value=" 0 " OnClick="Calculator.Input.value += '0'">  
<input type="button" name="DoIt" style="font-size:30px" value=" = " OnClick="Calculator.Input.value = eval(Calculator.Input.value)">  
<input type="button" name="div" style="font-size:30px" value=" / " OnClick="Calculator.Input.value += ' / '">  
<br>  
</td>  
 
</tr>  
</table>  
</form>  
      

    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: jQuery and Bootstrap Bundle (includes Popper) -->
    <script src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-Fy6S3B9q64WdZWQUiU+q4/2Lc9npb8tCaSX9FK7E8HnRr0Jz8D6OP9dO5Vg3Q9ct" crossorigin="anonymous"></script>

   
  </body>
</html>

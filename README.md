# my-first-calculator.
a simple function calculator with slight style
<head>
    <style>
        .card {
  border: 5px double;
  width: 310px;
  background-color: #000000;
  margin: auto;
  margin-top: 10%;
  padding: 10px;
  font-style: italic;
}

tr {
    height: 75px;
}


body{
  background: url('https://newevolutiondesigns.com/images/freebies/tech-wallpaper-1.jpg')
}
             /* Button styling */
.btn-style {
    width:50px;
    height:50px;
    margin-left:5px;
    border-radius:4px;
} 
.output-display{
  display: block;
  width: 277px;
}


    
    
</style>
</head>
<body>
    <div class='card'>
        <form name='calculator'>
  <table>
     <tr>
               <td colspan="5">
                  <input type="text"class='output-display' name="display" id="display" disabled>
               </td>
            </tr>
    <tr>
      <td><input type='button'name='seven'value='7'
     onclick="calculator.display.value += '7'">
      </td>
      <td><input type='button'name='eight'value='8'
                 onclick="calculator.display.value += '8'"></td> 
      <td><input type='button'name='nine'value='9'
                 onclick="calculator.display.value += '9'"></td>
      <td><input type='button'class='operator'=name='multiplication'value='x'
                 onclick="calculator.display.value += '*'"
                 ></td>
      <td><input type='button'class='operator'name='remainder'value='%'
                 onclick="calculator.display.value += '%'"></td>
    </tr>
   <td><input type='button'name='four'value='4'
       onclick="calculator.display.value += '4'" ></td>
   <td><input type='button'name='five'value='5' 
          onclick="calculator.display.value += '5'"></td>
           <td><input type='button'name='six'value='6'
                 onclick="calculator.display.value += '6'"></td>
   <td><input type='button'class='operator'name='subtraction'value='-'
         onclick="calculator.display.value += '-'">
   </td>
    <td><input type='button'name='pi'value="&Pi;"
               onclick="calculator.display.value = '3.14'"></td>
    
 <tr>
    <td><input type="button" name="one" value="1"
            onclick="calculator.display.value += '1'"></td>
    <td><input type='button'name='two'value='2' 
              onclick="calculator.display.value += '2'"></td>
   <td><input type='button'name='three'value='3'
              onclick="calculator.display.value += '3'"></td>
   <td><input type='button'class='operator'name='division'value='/'
               onclick="calculator.display.value += '/'">
      <td><input type='button'name='decimal'value='.'
                 onclick="calculator.display.value += '.'"
                 </td>
    </tr>
    <tr>  
      <td><input type='button'name='zero'value='0'
                 onclick="calculator.display.value +='0'"
                 ></td>
       <td><input type='button'class='operator'name='doit'value='='
                  onclick="calculator.display.value = eval(calculator.display.value)"
                 ></td> 
      <td><input type='button'id='clear'name='clear'value='c'
                 onclick="calculator.display.value = ''"></td>
  

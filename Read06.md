# Dynamic Webpages With JavaScript

JavaScript was invented by Brendan Eich in 1995. It is a lightweight programming language that is used to make dynamic and interactive websites. In order to use JS you must start by linking a JavaScript file to your html document. From there you are able to execute your script through variables, functions, input, and many other elements. Variables and functions both run inside your script tags or JS document where as input is something directly entered into your HTML document. There are so many different variations of these elements allowing users to create seemingly unlimited possibilites of code.

## JavaScript Examples

<html>
  
<head>
  
  <title>Hello World</title>
  
</head>
  
<body>
  
 
First name: <input id="first_name">
  
Last name: <input id="last_name">
  
<button id="say">Say hi!</button>
  
 
<hr>
  
<div id="result"></div>
  
 
<script>
  
function say_hi() {
  
    var fname = document.getElementById('first_name').value;
  
    var lname = document.getElementById('last_name').value;
 
    var html = 'Hello <b>' + fname + '</b> ' + lname;
 
    document.getElementById('result').innerHTML = html;
}
 
document.getElementById('say').addEventListener('click', say_hi);
</script>
  
 
</body>
  
</html>

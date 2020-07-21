<!DOCTYPE html>
<head><title>calculator</title></head>
<body><<h2>simple calculator</h2><button onclick="addition()">+</button>
<button onclick="subtraction()">-</button>
<button onclick="multiplication()">*</button>
<button onclick="division()">/</button>
<script>function addition() {
var n=parseInt(prompt ("enter a number")) ;
var m=parseInt(prompt("enter a number")) ;
var s=m+n;
alert(s) ;} 
function subtraction() {
var n=parseInt(prompt ("enter a number")) ;
var m=parseInt(prompt("enter a number")) ;
var s=m-n;
alert(s) ;}
function multiplication() {
var n=parseInt(prompt ("enter a number")) ;
var m=parseInt(prompt("enter a number")) ;
var s=m*n;
alert(s) ;} function division () {
var n=parseInt(prompt ("enter a number")) ;
var m=parseInt(prompt("enter a number")) ;
var s=n/m;alert(s) ;} 
</script>
</body>
</html>

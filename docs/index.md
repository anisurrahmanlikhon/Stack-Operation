
<html>
<body>
<title> Stack Operation </title>
<center>
<h1>Stack Operation </h1>

<button onclick="myFunction()">Push</button>

<p></p> <br>


<button onclick="myFunction1()">Pop</button><br>
<br>

<p id="demo"></p>

<p id="demo"></p>

<script>
var fruits = ["Banana", "Orange", "Apple", "Mango"];
document.getElementById("demo").innerHTML = fruits;

function myFunction() {
  fruits.push("Jackfruit");
  document.getElementById("demo").innerHTML = fruits;
}
</script>



<script>
var fruits = ["Banana", "Orange", "Apple", "Mango"]
document.getElementById("demo").innerHTML = fruits;

function myFunction1() {
  fruits.pop();
document.getElementById("demo").innerHTML = fruits;
}
</script>
</center>
</body>
</html>




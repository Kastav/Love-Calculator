<html>
<head>
  <title>Love Calculator</title>
</head>
<body>

<h2>Love Calculator ❤️</h2>

<input type="text" id="name1" placeholder="Your Name"><br><br>
<input type="text" id="name2" placeholder="Partner Name"><br><br>

<button onclick="love()">Check Love</button>

<p id="res"></p>

<script>
function love(){
  let percent = Math.floor(Math.random()*100) + 1;
  document.getElementById("res").innerText =
    "Love Percentage: " + percent + "%";
}
</script>

</body>
</html>

# temperature-BharatIntern-
<!DOCTYPE html>
<html>
<head>
<title>Temperature Converter</title>
<style>
body {
  font-family: sans-serif;
}

h1 {
  text-align: center;
}

input {
  width: 100px;
}

button {
  width: 100px;
}
</style>
</head>
<body>
<h1>Temperature Converter</h1>
<input type="text" id="celsius"><span> celsius </span> 
<button onclick="convert()">Convert</button>
<input type="text" id="fahrenheit"><span> fahrenheit </span>

<script>
function convert() {
  var celsius = document.getElementById("celsius").value;
  var fahrenheit = (celsius * 9 / 5) + 32;
  document.getElementById("fahrenheit").value = fahrenheit;
}
</script>
</body>
</html>


# my-first-project
this is my first GitHub project
<!DOCTYPE html>
<html>
<head>
<title>Bijli Bill Calculator - Gilgit</title>
<style>
body{font-family: Arial; text-align:center; background:#f0f8ff; padding:20px}
.box{background:white; padding:20px; border-radius:15px; max-width:400px; margin:auto; box-shadow:0 0 10px gray}
input,button{padding:10px; margin:10px; width:80%; border-radius:8px}
button{background:green; color:white; border:none; cursor:pointer}
</style>
</head>
<body>
<div class="box">
<h2>Bijli Bill Calculator</h2>
<input type="number" id="units" placeholder="Kitne Units Use Hue?">
<button onclick="calculate()">Bill Calculate Karo</button>
<h3 id="result"></h3>
</div>
<script>
function calculate(){
let u = document.getElementById("units").value;
let bill = u * 25; // 1 unit = 25 rupay
document.getElementById("result").innerText = "Aapka Bill: Rs " + bill;
}
</script>
</body>
</html>

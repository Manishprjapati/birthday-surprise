<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>For My Special One ❤️</title>

<style>
body {
  margin: 0;
  font-family: Arial;
  background: linear-gradient(to right, #ff758c, #ff7eb3);
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}

.container {
  background: white;
  padding: 40px;
  border-radius: 20px;
  text-align: center;
  width: 300px;
}

button {
  background: #ff4d6d;
  border: none;
  padding: 10px 20px;
  color: white;
  border-radius: 10px;
  cursor: pointer;
}

#hidden {
  display: none;
  margin-top: 20px;
}

.heart {
  font-size: 24px;
}
</style>

</head>

<body>

<div class="container">
  <h1>Hey Beautiful ❤️</h1>

  <p>
    I know tum naraz ho...<br>
    but you mean everything to me 🌍
  </p>

  <button onclick="showLove()">Click Me 🥺</button>

  <div id="hidden">
    <h2>I’m Sorry 💔</h2>
    <p>
      Tumhari smile meri favorite cheez hai.<br>
      Please maan jao yaar 🥹❤️
    </p>
    <p class="heart">❤️ ❤️ ❤️</p>
  </div>
</div>

<script>
function showLove() {
  document.getElementById("hidden").style.display = "block";
}
</script>

</body>
</html>

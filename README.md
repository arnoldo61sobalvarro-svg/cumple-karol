<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Feliz Cumpleaños ❤️</title>

<style>
body{
font-family: Arial;
text-align:center;
background:linear-gradient(135deg,#ff9a9e,#fad0c4);
color:white;
margin-top:100px;
}

button{
padding:20px;
font-size:20px;
background:#ff4d6d;
border:none;
border-radius:10px;
color:white;
cursor:pointer;
}

#sorpresa{
display:none;
margin-top:40px;
}

img{
width:250px;
margin:10px;
border-radius:15px;
}

</style>
</head>

<body>

<h1>🎉 Feliz Cumpleaños Mi Amor 🎉</h1>
<p>Hoy celebro la suerte de tenerte ❤️</p>

<button onclick="mostrar()">💖 Toca aquí 💖</button>

<div id="sorpresa">

<h2>Te amo muchísimo</h2>

<img src="foto1.jpg">
<img src="foto2.jpg">
<img src="foto3.jpg">

<p>Eres la persona más especial de mi vida 💕</p>

<audio controls autoplay>
<source src="cumple.mp3" type="audio/mpeg">
</audio>

</div>

<script>
function mostrar(){
document.getElementById("sorpresa").style.display="block";
}
</script>

</body>
</html>

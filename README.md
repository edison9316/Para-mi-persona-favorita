<img width="1152" height="2048" alt="foto" src="https://github.com/user-attachments/assets/63bc0745-67c8-4c2a-ac07-510e3165dfca" />
# Para-mi-persona-favorita
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Para Paulina ❤️</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family: Georgia, serif;
}

html{
scroll-behavior:smooth;
}

body{
background:#000;
overflow-x:hidden;
}

.hero{
height:100vh;
background:url('foto.jpg') center center/cover no-repeat;
position:relative;
display:flex;
justify-content:center;
align-items:center;
}

.overlay{
position:absolute;
inset:0;
background:rgba(0,0,0,.45);
backdrop-filter:blur(1px);
}

.contenido{
position:relative;
z-index:2;
text-align:center;
color:white;
padding:20px;
max-width:700px;
animation:fadeIn 2s ease;
}

h1{
font-size:2.4rem;
margin-bottom:20px;
text-shadow:0 0 20px rgba(255,255,255,.4);
}

.sub{
font-size:1.2rem;
line-height:1.6;
margin-bottom:35px;
}

.boton{
background:white;
color:black;
padding:16px 34px;
border-radius:50px;
border:none;
font-size:1rem;
font-weight:bold;
cursor:pointer;
transition:.3s;
}

.boton:hover{
transform:scale(1.05);
}

.carta{
display:none;
background:#fffaf5;
padding:50px 25px;
}

.carta-contenido{
max-width:750px;
margin:auto;
color:#333;
line-height:2;
font-size:1.15rem;
}

.titulo-carta{
text-align:center;
font-size:2rem;
margin-bottom:35px;
color:#b76e79;
}

.spotify{
text-align:center;
margin-top:50px;
}

.spotify a{
display:inline-block;
padding:16px 32px;
background:#1DB954;
color:white;
text-decoration:none;
border-radius:40px;
font-weight:bold;
}

.firma{
margin-top:45px;
text-align:right;
font-style:italic;
font-size:1.2rem;
}

.corazon{
position:fixed;
top:-20px;
pointer-events:none;
animation:caer linear infinite;
opacity:.5;
z-index:999;
}

@keyframes caer{
from{
transform:translateY(-10vh);
}
to{
transform:translateY(110vh);
}
}

@keyframes fadeIn{
from{
opacity:0;
transform:translateY(25px);
}
to{
opacity:1;
transform:translateY(0);
}
}

</style>
</head>

<body>

<section class="hero">

<div class="overlay"></div>

<div class="contenido">

<h1>❤️ Para Paulina ❤️</h1>

<p class="sub">
Porque algunas personas llegan y hacen que todo sea diferente.
</p>

<button class="boton" onclick="mostrarCarta()">
Abrir ❤️
</button>

</div>

</section>

<section class="carta" id="carta">

<div class="carta-contenido">

<h2 class="titulo-carta">
Feliz Cumpleaños, Paulina ❤️
</h2>

<p>
Hoy empieza un mes especial, porque es el mes en el que llegó al mundo una persona que, sin esperarlo, se ha vuelto muy importante para mí.
</p>

<br>

<p>
Hace relativamente poco que nos conocemos, pero hay conexiones que no necesitan años para sentirse reales. Contigo todo ha sido fácil, natural y diferente desde el principio.
</p>

<br>

<p>
Me encanta cada conversación, cada risa compartida y esa forma tan especial que tenemos de entendernos. Hay momentos que parecen pequeños, pero contigo terminan convirtiéndose en recuerdos que guardo con mucho cariño.
</p>

<br>

<p>
Quizás todavía no podamos ponerle un nombre a todo lo que estamos construyendo, pero sí puedo decir que disfruto cada paso que damos juntos. Porque aunque oficialmente no seamos novios, hay muchas cosas entre nosotros que ya se sienten como algo mucho más grande.
</p>

<br>

<p>
Lo que más deseo para ti en este cumpleaños es que seas feliz, que cumplas cada uno de tus sueños y que nunca pierdas esa luz tan bonita que tienes.
</p>

<br>

<p>
Y si me permites pedir un deseo para mí, sería seguir compartiendo momentos contigo, seguir descubriéndote y seguir construyendo esta historia que empezó de una manera tan inesperada y tan bonita.
</p>

<br>

<p>
Gracias por aparecer en mi vida, Paulina.
</p>

<div class="firma">
Con muchísimo cariño ❤️
</div>

<div class="spotify">
<a href="https://open.spotify.com/track/6aiToGHHG0JmYhEymBtaIJ?si=HIvqy7fjQmKzclO01KKCkg" target="_blank">
🎵 Escuchar nuestra canción
</a>
</div>

</div>

</section>

<script>

function mostrarCarta(){
document.getElementById('carta').style.display='block';

setTimeout(()=>{
document.getElementById('carta').scrollIntoView({
behavior:'smooth'
});
},200);
}

for(let i=0;i<25;i++){

let corazon=document.createElement('div');

corazon.className='corazon';
corazon.innerHTML='❤️';

corazon.style.left=Math.random()*100+'vw';
corazon.style.fontSize=(15+Math.random()*20)+'px';
corazon.style.animationDuration=(6+Math.random()*8)+'s';

document.body.appendChild(corazon);
}

</script>

</body>
</html>

<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Estética Yireh</title>

<style>

body{
font-family: Arial, sans-serif;
margin:0;
background:#fdecec;
color:#333;
}

header{
background:linear-gradient(90deg,#f7c6c6,#fbe4e4);
padding:60px 20px;
text-align:center;
}

header h1{
margin:0;
font-size:42px;
color:#b56b6b;
}

header p{
font-size:20px;
margin:10px 0;
}

section{
padding:50px 20px;
max-width:1200px;
margin:auto;
}

h2{
text-align:center;
color:#b56b6b;
}

.services{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
margin-top:30px;
}

.card{
background:white;
border-radius:15px;
box-shadow:0 6px 18px rgba(0,0,0,0.1);
padding:25px;
text-align:center;
}

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:15px;
margin-top:30px;
}

.gallery img{
width:100%;
border-radius:12px;
height:220px;
object-fit:cover;
}

.prices{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:20px;
margin-top:30px;
}

.price-card{
background:white;
border-radius:15px;
padding:25px;
text-align:center;
box-shadow:0 5px 15px rgba(0,0,0,0.1);
}

.price{
font-size:26px;
color:#b56b6b;
font-weight:bold;
}

.reviews{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
margin-top:30px;
}

.review{
background:white;
border-radius:15px;
padding:20px;
box-shadow:0 5px 15px rgba(0,0,0,0.1);
}

.contact{
background:#f7c6c6;
padding:40px;
border-radius:15px;
text-align:center;
margin-top:30px;
}

footer{
text-align:center;
padding:25px;
background:#fbe4e4;
margin-top:40px;
}

button{
background:#b56b6b;
color:white;
border:none;
padding:14px 22px;
border-radius:10px;
font-size:16px;
cursor:pointer;
}

button:hover{
background:#944f4f;
}

.whatsapp{
position:fixed;
bottom:20px;
right:20px;
background:#25D366;
color:white;
padding:15px 18px;
border-radius:50px;
font-weight:bold;
text-decoration:none;
box-shadow:0 5px 15px rgba(0,0,0,0.2);
}

iframe{
width:100%;
height:350px;
border:0;
border-radius:15px;
margin-top:25px;
}

</style>
</head>

<body>

<header>

<h1>Estética Yireh</h1>

<p>Cortes profesionales a domicilio</p>

<button onclick="window.location.href='https://wa.me/525620563503?text=Hola%20quiero%20agendar%20un%20corte%20a%20domicilio'">
Agendar cita por WhatsApp
</button>

</header>

<section>

<h2>Servicios</h2>

<div class="services">

<div class="card">
<h3>Corte de Caballero</h3>
<p>Corte moderno y profesional sin salir de casa.</p>
</div>

<div class="card">
<h3>Corte de Dama</h3>
<p>Estilo, elegancia y tendencia en cada servicio.</p>
</div>

<div class="card">
<h3>Corte Infantil</h3>
<p>Cortes cómodos y rápidos para los más pequeños.</p>
</div>

<div class="card">
<h3>Peinados</h3>
<p>Peinados para eventos especiales.</p>
</div>

</div>

</section>

<section>

<h2>Galería de Cortes</h2>

<div class="gallery">

<img src="corte1.jpg">
<img src="corte2.jpg">
<img src="corte3.jpg">
<img src="corte4.jpg">
<img src="corte5.jpg">
<img src="corte6.jpg">
<img src="corte7.jpg">

</div>

</section>

<section>

<h2>Lista de Precios</h2>

<div class="prices">

<div class="price-card">
<h3>Corte Caballero</h3>
<p class="price">$120</p>
</div>

<div class="price-card">
<h3>Corte Dama</h3>
<p class="price">$150</p>
</div>

<div class="price-card">
<h3>Corte Niño</h3>
<p class="price">$100</p>
</div>

<div class="price-card">
<h3>Peinados</h3>
<p class="price">Desde $180</p>
</div>

</div>

</section>

<section>

<h2>Opiniones de Clientes</h2>

<div class="reviews">

<div class="review">
<p>"Excelente servicio, muy profesional y puntual."</p>
<strong>- Cliente</strong>
</div>

<div class="review">
<p>"Me encantó mi corte, definitivamente volveré a llamar."</p>
<strong>- Cliente</strong>
</div>

<div class="review">
<p>"Muy práctico que el servicio sea a domicilio."</p>
<strong>- Cliente</strong>
</div>

</div>

</section>

<section>

<h2>Contacto</h2>

<div class="contact">

<p><strong>Teléfono:</strong> 56 20 56 35 03</p>

<p><strong>Email:</strong> 78sanchez.lucy@gmail.com</p>

<p>Cortes profesionales a domicilio</p>

</div>

<iframe src="https://www.google.com/maps?q=Ciudad+de+Mexico&output=embed"></iframe>

</section>

<footer>

<p>© 2026 Estética Yireh - Todos los derechos reservados</p>

</footer>

<a class="whatsapp"
href="https://wa.me/525620563503?text=Hola%20quiero%20agendar%20un%20corte%20a%20domicilio"
target="_blank">

WhatsApp

</a>

</body>
</html>

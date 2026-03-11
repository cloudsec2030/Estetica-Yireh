<style>

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
cursor:pointer;
transition:transform 0.3s, box-shadow 0.3s;
}

.gallery img:hover{
transform:scale(1.05);
box-shadow:0 10px 25px rgba(0,0,0,0.2);
}

/* visor de imagen */

.lightbox{
display:none;
position:fixed;
top:0;
left:0;
width:100%;
height:100%;
background:rgba(0,0,0,0.8);
justify-content:center;
align-items:center;
z-index:999;
}

.lightbox img{
max-width:90%;
max-height:80%;
border-radius:12px;
}

</style>


<section>

<h2>Galería de Cortes</h2>

<div class="gallery">

<img src="corte1.jpg" onclick="openImg(this)" onerror="this.remove()">
<img src="corte2.jpg" onclick="openImg(this)" onerror="this.remove()">
<img src="corte3.jpg" onclick="openImg(this)" onerror="this.remove()">
<img src="corte4.jpg" onclick="openImg(this)" onerror="this.remove()">
<img src="corte5.jpg" onclick="openImg(this)" onerror="this.remove()">
<img src="corte6.jpg" onclick="openImg(this)" onerror="this.remove()">
<img src="corte7.jpg" onclick="openImg(this)" onerror="this.remove()">

</div>

</section>


<div class="lightbox" id="lightbox" onclick="closeImg()">
<img id="lightbox-img">
</div>


<script>

function openImg(img){
document.getElementById("lightbox").style.display="flex";
document.getElementById("lightbox-img").src=img.src;
}

function closeImg(){
document.getElementById("lightbox").style.display="none";
}

</script>

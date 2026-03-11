<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<title>İyi Ki Doğdun</title>

<style>

body{
font-family: Arial;
background: linear-gradient(120deg,#ff9a9e,#fad0c4);
text-align:center;
padding:50px;
}

.card{
background:white;
padding:30px;
border-radius:20px;
max-width:600px;
margin:auto;
box-shadow:0 10px 30px rgba(0,0,0,0.2);
}

h1{
color:#ff4081;
}

.gallery{
margin-top:20px;
}

.gallery img{
width:150px;
height:150px;
object-fit:cover;
border-radius:15px;
margin:10px;
}

button{
padding:12px 20px;
font-size:16px;
border:none;
border-radius:10px;
background:#ff4081;
color:white;
cursor:pointer;
}

</style>
</head>

<body>

<div class="card">

<h1>🎉 İyi ki Doğdun!</h1>

<p>
Hayatımda olduğun için çok mutluyum.  
İyi ki varsın. Doğum günün kutlu olsun ❤️
</p>

<button onclick="showPhotos()">Fotoğrafları Göster</button>

<div class="gallery" id="photos" style="display:none">

<img src="foto1.jpg">
<img src="foto2.jpg">
<img src="foto3.jpg">

</div>

</div>

<script>

function showPhotos(){
document.getElementById("photos").style.display="block";
}

</script>

</body>
</html>

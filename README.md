<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>LA 237 | Despertando conciencias</title>

<link href="https://fonts.googleapis.com/css2?family=Oswald:wght@400;700&display=swap" rel="stylesheet">

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    background:#000;
    font-family:'Oswald', sans-serif;
    color:white;
    min-height:100vh;

    display:flex;
    justify-content:center;
    align-items:center;

    text-align:center;

    background:linear-gradient(to bottom,#2b0000,#000);
}

.container{
    width:100%;
    max-width:420px;
    padding:20px;
}

/* LOGO IMAGEN */
.logo-img{
    width:120px;
    height:120px;
    object-fit:cover;
    border-radius:50%;
    margin-bottom:20px;

    border:2px solid red;

    box-shadow:
    0 0 10px red,
    0 0 20px red,
    0 0 40px rgba(255,0,0,0.7);
}

/* TEXTO PRINCIPAL */
.logo{
    font-size:48px;
    letter-spacing:4px;
    margin-bottom:10px;

    animation:fadeIn 2s ease;
}

.lema{
    font-size:14px;
    opacity:0.7;
    margin-bottom:40px;

    animation:fadeIn 3s ease;
}

/* BOTONES */
.links a{
    display:block;

    text-decoration:none;
    color:white;

    padding:16px;
    margin-bottom:20px;

    border:2px solid red;
    border-radius:50px;

    background:#050505;

    font-size:18px;
    font-weight:bold;

    transition:0.3s;

    box-shadow:
    0 0 10px red,
    0 0 20px rgba(255,0,0,0.5);
}

.links a:hover{
    transform:scale(1.05);

    background:red;
    color:black;

    box-shadow:
    0 0 20px red,
    0 0 40px red;
}

/* FOOTER */
.footer{
    margin-top:35px;

    font-size:12px;
    opacity:0.5;
}

/* ANIMACIÓN */
@keyframes fadeIn{
    from{
        opacity:0;
        transform:translateY(20px);
    }

    to{
        opacity:1;
        transform:translateY(0);
    }
}

</style>
</head>

<body>

<div class="container">

<!-- IMAGEN -->
<img src="img/logo.jpeg" alt="Logo LA 237" class="logo-img">

<!-- TITULO -->
<div class="logo">LA 237</div>

<!-- FRASE -->
<div class="lema">
Despertando conciencias en este mundo de apariencias
</div>

<!-- REDES -->
<div class="links">

<a href="https://www.facebook.com/share/1CGRwtJomv/" target="_blank">
FACEBOOK
</a>

<a href="https://www.instagram.com/lazona237?igsh=b2FyZTBsa3JodTds" target="_blank">
INSTAGRAM
</a>

<a href="https://youtube.com/@la-rw3pb?si=T1TgSEtkIUs0bnzU" target="_blank">
YOUTUBE
</a>

<a href="https://www.tiktok.com/@la23779?_r=1&_t=ZS-93sM1vMkLJN" target="_blank">
TIKTOK
</a>

</div>

<!-- FOOTER -->
<div class="footer">
© 2026 LA 237 - Todos los derechos reservados
</div>

</div>

</body>
</html>

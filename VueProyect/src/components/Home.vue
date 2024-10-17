<template>
    <header id="inicio">
        <nav class="MenuInicial">
            <a href="#inicio">INICIO</a>
            <a href="#servicios">SERVICIOS</a>
            <img src="/public/img/LogoB.png" alt="Logo">
            <a href="#galeria">GALERÍA</a>
            <a href="#contacto">CONTACTANOS</a>
        </nav>
        <div class="TextBienvenida">
            <span><img src="/public/svg/comillasLeft.svg" alt="Comillas"><strong>TU NEGOCIO </strong><i>AL MUNDO REAL</i><img src="/public/svg/comillasRith.svg" alt="Comillas"></span> 
        </div>
        <div class="MenuRedes">
            <a href="https://api.whatsapp.com/send?phone=955500224" target="_blank"><img src="/public/svg/brand-whatsapp.svg" alt="WhatsApp"></a>
            <a href="https://www.instagram.com/amacreative_design/" target="_blank"><img src="/public/svg/brand-instagram.svg" alt="Instagram"></a>
            <a href="https://www.facebook.com/people/Ama-Creative-Desing/61559881574717/" target="_blank"><img src="/public/svg/brand-facebook.svg" alt="Facebook"></a>
        </div>
    </header>
</template>

<script setup></script>
<style>
/* Ajustes generales */
* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

a {
    text-decoration: none;
}

/* Inicio */
header {
    height: 100vh;
    width: 100%;
    background-image: url(/src/assets/img/FondoInicial.jpg);
    background-size: cover;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

.MenuInicial {
    height: 130px;
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    align-items: center;
}

.MenuInicial > a {
    color: white;
}

.MenuInicial > img {
    width: 100px;
}

.TextBienvenida {
    display: flex;
    justify-content: center;
}

.TextBienvenida > span {
    font-size: 50px;
}

.TextBienvenida > span > img {
    height: 50px;
}

.TextBienvenida > span {
    color: white;
}

.MenuRedes {
    padding-bottom: 50px;
    display: flex;
    justify-content: flex-start;
    flex-direction: column; /* Cambiado a 'row' para alinear los iconos horizontalmente */
    align-items: start; /* Cambiado a 'center' para alinear verticalmente los iconos */
}

.MenuRedes > a > img {
    height: 55px;
    width: 55px; /* Ajustar el tamaño de los iconos */
    padding: 8px;
}

.MenuRedes > a {
    margin: 10px;
}

.MenuRedes > a:hover {
    background-color: rgba(240, 248, 255, 0.171);
    border-radius: 10px;
}
</style>
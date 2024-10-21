<template>
    <div id="contacto">
        <h3>TU MEJOR <span style="color:#6B3CC8;">EXPERIENCIA</span> COMIENZA AQUÍ</h3>
        <div class="contacto-contenido">
            <div class="form-Contacto">
                <div style="display: flex; flex-direction: row; justify-content: space-between;">
                    <div>
                        <label for="">Nombre</label>
                        <input type="text" name="Name" id="">
                    </div>
                    <div>
                        <label for="" class="InputLastname">Apellido</label>
                        <input type="text" name="" id="LastName">
                    </div>
                </div>
                <div>
                    <label for="">Correo</label>
                    <input type="email" name="" id="">
                </div>
                <div>
                    <label for="">Mensaje</label>
                    <textarea rows="4"></textarea>
                </div>
                <div>
                    <label for="" style="color:#A798E4;">Condiciones Legales</label>
                    <span><input type="checkbox">Acepto las condiciones generales de <a href="#" style="color:#A798E4;">Política de privacidad</a> y <a href="#" style="color:#A798E4;">Aviso legal</a></span>
                </div>
                <span><button type="submit" style="background-color:#5F38AE;color: white;">ENVIAR</button></span>
            </div>
            <div class="map-container">
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d975.7259748426005!2d-77.08318512573761!3d-11.981151220677152!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x9105cf75261ea4af%3A0xb624a558e6aa0050!2sMZ.%20F%20Los%20jazmines%20de%20naranjal!5e0!3m2!1ses-419!2spe!4v1718462150338!5m2!1ses-419!2spe" width="800" height="600" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
            </div>
        </div>
    </div>
</template>
<script setup></script>
<style>
* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    font-family: 'RegularAlbert';
}

a {
    text-decoration: none;
}
/*contactos*/

#contacto{
    background-image: url(/public/img/fondoTercero.png);
    background-size: cover;
    background-position:center;
    width: 100%;
    height: 100vh;
    color: white;
}

#contacto > h3{
    font-family: 'AlbertSansExtraBold';
    text-align: center;
    padding:40px 0;
    font-size: 40px;
}

.contacto-contenido{
    display: flex;
    align-items: center;
    justify-content: space-around;
}

.form-Contacto, .map-container{
    width: 40%;
}
.form-Contacto{
    display: flex;
    flex-direction: column;
}

.form-Contacto > div{
    display: flex;
    flex-direction: column;
}
.form-Contacto > div >div{
    display: flex;
    flex-direction: column;
}

.form-Contacto > div >div>input{
    width: 200%;
    height: 50px;
    border-radius: 13px;
}

.form-Contacto > div >input{
    width: 100%;
    height: 50px;
    border-radius: 13px;
}

.form-Contacto > div >textarea{
    height: 150px;
    border-radius: 13px;
}


#LastName, .InputLastname{
    margin-left: -100%;
}

.form-Contacto > span{
    display: flex;
    padding: 30px;
    justify-content: center;
}

.form-Contacto > span> button{
    padding: 10px 20px;
    text-align: center;
    font-size: 25px;
    border-radius: 13px;
}

.map-container > iframe{
    height: 600px;
    width: 600px;
}
</style>
<template>
    <footer>
        <div class="footer-container">
            <div class="footer-left">
                <img src="/public/img/LogoB.png" alt="LogoM" >
            </div>
            <div class="footer-right">
                    <div class="SectionDirect">
                        <div class="footer-item">
                            <img src="/public/svg/phone-solid.svg" alt="phone-solid">
                        </div>
                        <div>
                            <a href="tel:+51955500224">+51 955 500 224</a>
                        </div>
                    </div>
                    <div class="SectionDirect">
                        <div class="footer-item">
                            <img src="/public/svg/envelope-regular.svg" alt="envelope-regular">
                        </div>
                        <div>
                            <a href="mailto:alberto.diaz@amacreative.me">alberto.diaz@amacreative.me</a>
                            <br>
                            <a href="mailto:alberto.diaz.ama@gmail.com">alberto.diaz.ama@gmail.com</a>
                        </div>
                    </div>
                    <div class="SectionDirect">
                        <div class="footer-item">
                            <img src="/public/svg/location-dot-solid.svg" alt="location-dot-solid">
                        </div>
                        <address>
                            Jr. Virgo 1193, Urb. Mercurio<br>
                            Los Olivos - Lima Norte
                        </address>
                    </div>
            </div>
        </div>
    </footer>
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
    color: black;
}

/*footer*/
footer {
    width: 100%;
    height: 33vh;
    background-color: #2d0bc4;
    display: flex;
    align-items: center;
    justify-content: center;
}

.footer-container {
    width: 90%;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.footer-left img {
    max-width: 25%;
    margin-left: 100px;
}

.footer-right {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
    margin-right: 100px;
}

.SectionDirect{
    display: flex;
    flex-direction: row;
    margin: 8px;
    font-size: 20px;
}

.footer-item {
    display: flex;
    align-items: center;
    margin: 5px 0;
}

.footer-item img {
    width: 20px;
    margin-right: 10px;
}

</style>
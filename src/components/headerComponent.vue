<template lang="">
    <div class="header">
        <div class="contenitore-header">
            <div class="contenitore-immagine">
                <img src="../assets/img/logo.png" alt="">
            </div>
            <div class="contenitore-testo">
                <ul>
                    <li>Climatizzazione e Riscaldamento</li>
                    <li>Refrigerazione industriale</li>
                    <li>Assistenza tecnica</li>
                    <li>Manutenzione</li>
                    <li>Consulenza energetica</li>
                </ul>
            </div>
        </div>
        <div class="contenitore-nav">
            <nav>
                <ul>
                    <li><a href="">Home</a></li>
                    <li><a href="">Il servizio</a></li>
                    <li><a href="">Il team</a></li>
                    <li><a href="">La nostra storia</a></li>
                    <li><a href="">Manutenzione</a></li>
                    <li><a href="">Tutto normativa</a></li>
                    <li><a href="">Sanificazione</a></li>
                    <li><a href="">Contatti</a></li>
                </ul>
            </nav>
        </div>
    </div>
</template>
<script>
export default {
    name: "headerComponent"
}
</script>
<style scoped lang="scss">
.header .contenitore-header {
    margin: 0 auto;
    max-width: 1000px;
    background-color: #ffffff;
    display: flex;
    gap: 50px;
}
.header .contenitore-testo {
    font-family: 'Century Gothic', 'Avant Garde', Muli, sans-serif;
    font-size: 18px;
    font-style: italic;
    font-weight: normal;
    color: #051972;
    line-height: 1.2em;
    text-align: left;
}

.header .contenitore-nav {
    background-color: #003853;
    margin: 0 auto;
    max-width: 1000px;
    ul {
        height: 50px;
        display: flex;
        justify-content: space-around;
        li {
            color: #65bde2;
            padding-top: 15px;
        }
        li:hover {
            color: #ffffff;
            cursor: pointer;
        }
        li:active {
            background-color: rgb(0, 45, 75);
        }
        li:visited {
            background-color: red;
        }
        a {
            margin-top: 20px;
        }
       
    }
}
</style>
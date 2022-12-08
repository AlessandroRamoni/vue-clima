<template>
  <div class="contenitore-home">
    <div class="contenitore-sx">
      <div class="button">
        <button><a href="#">ACCESSO PORTALE MR</a></button>
      </div>
      <div class="testo">
        <p>Per richiedere le vostre credenziali d'accesso scrivere a:</p>
        <span><a href="#">tecnico@mrcentroclima.it</a></span>
        <p>Centro assistenza autorizzato:</p>
      </div>
      <div class="immagini">
        <img src="../assets/img/loghi_vari.jpg" alt="loghi vari">
      </div>
      <hr>
      <div class="contatti">
        <h2>Come contattarci:</h2>
        <img src="../assets/img/contatti.jpg" alt="contatti">
        <h3>Sede legale e operativa:</h3>
        <p>Via Milano, 316/3</p>
        <p>21020 Mercallo VA</p>
        <h3>Telefono:</h3>
        <p>0331.969067</p>
        <h3>E-mail:</h3>
        <p>info@mrcentroclima.it</p>
        <h1>Orari di apertura</h1>
        <table>
          <tr>
            <td>Lunedì-Venerdì</td>
            <td>08:00 - 12:30</td>
          </tr>
          <tr>
            <td></td>
            <td>13:30 - 17:30</td>
          </tr>
        </table>
      </div>
    </div>
    <div class="contenitore-dx">
      <div class="immagine">
        <hr>
        <img src="../assets/img/clouds.png" alt="clouds">
        <hr>
      </div>
      <div class="descrizione">
        <p>La MR CENTRO CLIMA s.r.l. é in grado di offrire un servizio di assistenza tecnica specializzata, consulenza energetica e ingegneristica su tutti gli impianti di climatizzazione/riscaldamento, refrigerazione industriale, compresi contratti annuali di manutenzione atti a migliorare l'efficienza dei vostri impianti.</p>
        <p>
Una flotta di 12 mezzi e 11 tecnici frigoristi specializzati con patentino Fgas categoria 1 permettono di garantire interventi tempestivi in ogni periodo dell'anno.</p>

      </div>
      <hr>
      <div class="carosello">
        <h2>NOVITA' 2018 : QUALIFICA ISO 9001:2015</h2>
        <p>MR Centro Clima Srl ha acquisito la certificazione ISO 9001:2015 per la Manutenzione e conduzione di impianti termici come terzo responsabile</p>
      </div>
      <hr>
    </div>
  </div>
</template>

<script>
export default {
  name: 'homeComponent',

}
</script>


<style scoped lang="scss">

.contenitore-home {
  display: flex;
  margin: 0 auto;
    max-width: 1000px;
}

.contenitore-sx {
  flex-basis: 30%;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.contenitore-dx {
  flex-basis: 70%;
}

.button {
    width: 200px;
    background-color: #003853;
    color: #e6ebee;
    border-radius: 5px;
    padding: 10px 5px;
    // position: absolute;
    // top: 50%;
    // left: 50%;
    // transform: translate(-50%, -50%);
  }

  .testo p {
    color: #03579B;
  }

  .testo span a {
      text-decoration: underline;
    }

    .contatti h2, h3{
      color: #03579B;
      font-family: 'Georgia', 'Times New Roman', serif;
      font-style: normal;
      font-weight: bold;
    }

    .contenitore-dx > * {
      padding-top: 30px;
    }

    .contenitore-sx > * {
      margin-top: 50px;
    }

    .contenitore-dx .carosello h2 {
      font-family: Helvetica, 'Helvetica Neue', 'Trebuchet MS', sans-serif;
      font-style: normal;
      font-size: 16px;
      color: #03579b;
      font-weight: bold;
    }

    .contenitore-dx .descrizione p {
      color:#000000;
      font-family: Helvetica, 'Helvetica Neue', 'Trebuchet MS', sans-serif;
      font-style: normal;
      font-size: 16px;
      font-weight: normal;
      line-height: 1.35;
      text-align: left;
      padding-top: 20px;
    // -webkit-font-smoothing: antialiased;
    // text-rendering: optimizeLegibility;
    }

    hr {
      border-color: #bababa;
      border-bottom-style: solid;
      border-bottom-width: 1px;
    }
</style>

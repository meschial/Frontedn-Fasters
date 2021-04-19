<template>
  <div class="tuxedo">
    <div class="row">
      <div class="col-7">
        <div class="text">
          <h1>Condição Imperdível</h1>
          <ul>
            <li>
              <span> </span>
              <p> é <b class="letra"> 10 meses</b> para confeccionar sua roupa e não se preocupe se<br>
                <span class="marg"></span> suas medidas aumentaram ou diminuíram, estará sempre elegante;
              </p>
            </li>
            <li>
              <span> </span>
              <p> Poder presentear alguém com uma roupa de alta costura, <b class="letra">  exclusiva; </b></p>
            </li>
            <li>
              <span> </span>
              <p> Garante uma condição muito especial por <b class="letra"> tempo limitado;</b> </p>
            </li>
            <li>
              <span>  </span>
              <p> 12% de desconto e pagamento em até <b class="letra"> 3x sem juros. </b></p>
            </li>
          </ul>
          <div class="condicao">
            <a href="#" class="a_button">Agente uma visita!</a>
          </div>
        </div>
      </div>
      <div class="col-4">
        <div class="image">
          <img src="../../assets/img/terno.png">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'TuxedoComponent'
}
</script>

<style lang="scss" scoped>
@import '@/assets/scss/_main.scss';
.tuxedo{
  background-image: linear-gradient(to right,#013145 , #063e57);
  .row{
    margin: 0;
  }
}
.text{
    margin-left: 20%;
    margin-top: 50px;
    h1{
      margin-left: 35px;
      margin-bottom: 35px;
      font-family: 'Cormorant';
      font-style: normal;
      font-weight: normal;
      font-size: 53px;
      line-height: 64px;
      text-transform: uppercase;
      color: #BE9667;
      text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
    }
    ul{
      li{
        list-style: none;
        color:#C4C4C4;
        font-family: 'Lato';
        font-style: normal;
        font-weight: 300;
        font-size: 22px;
        line-height: 26px;
        margin-bottom: 30px;
        span{
          float: left;
          margin-right: 10px;
          color: #BE9667;
          width: 20px;
          margin-top: 10px;
          border-top: 1px solid #BE9667;
        }
        .letra{
          font-weight: 400;
        }
        .marg{
          border: none;
        }
      }
    }
    .condicao{
      margin-left: 35px;
      margin-top: 50px;
      margin-bottom: 50px;
      .a_button{
        text-decoration: none;
        padding: 10px 35px;
        background-color: #BE9667;
        color: #E0E0E0;
        font-family: 'Lato';
        font-style: normal;
        font-weight: normal;
        font-size: 18px;
      }
    }
  }
  .image{
    padding: 20px 0;
    margin-left: 100px;
  }

</style>

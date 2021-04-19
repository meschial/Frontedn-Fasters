<template>
  <div class="container">
    <div class="shirt">
      <div class="row">
        <div class="col-6">
          <div class="text">
            <h1>Alfaiataria</h1>
            <span>- totalmente feito a mão sob medida</span>
            <div class="row">
              <div class="col-6">
                <ul>
                  <li>Fio Super 120 e 130 </li>
                  <li>Lã fria Australiana</li>
                  <li>Botões Importados</li>
                </ul>
              </div>
              <div class="col-6">
                <ul>
                  <li>Ternos e Calças</li>
                  <li>Paletós e Smokings</li>
                  <li>Sociais e Esportivos</li>
                </ul>
              </div>
            </div>
            <div class="orcamento_buttom">
              <a href="#" class="a_button">faça um orçamento</a>
            </div>
          </div>
        </div>
        <div class="bordeText"></div>
        <div class="col-6">
          <div class="imgBorder"></div>
          <img src="../../assets/img/alf.png">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'TailoringComponent'
}
</script>

<style lang="scss" scoped>
@import '@/assets/scss/_main.scss';
.container, .container-sm, .container-md, .container-lg, .container-xl {
    max-width: 1275px;
}
.shirt{
  margin: 50px 0;
  .col-6{
    z-index: 2;
  }
  .imgBorder{
    position: absolute;
    width: 560px;
    margin-top: 15px;
    height: 460px;
    border: 2px solid #1C86A4;
  }
  img{
    margin-left: 15px;
  }
  .bordeText{
    border: 1px solid  #E5E5E5;
    width: 720px;
    height: 400px;
    margin-top: 50px;
    position: absolute;
  }
  .text{
    margin: 70px 0 0 30px;
    h1{
      font-family: 'Cormorant';
      font-style: normal;
      font-weight: 300;
      font-size: 62px;
      line-height: 75px;
      color: $azul;
    }
    span{
      font-family: 'Lato';
      font-style: normal;
      font-weight: normal;
      font-size: 16px;
      line-height: 19px;
      position: absolute;
      margin-top: -20px;
      text-transform: uppercase;
      color: #C4C4C4;
    }
    ul{
      margin-top: 50px;
      li{
        font-family: 'Cormorant';
        font-style: italic;
        font-weight: normal;
        font-size: 24px;
        line-height: 29px;
        color: #727272;
      }
    }
    .orcamento_buttom{
      margin-top:50px;
      .a_button{
        color: $branco;
        text-decoration: none;
        text-transform: uppercase;
        background-color: $azul;
        padding: 12px 40px;
        font-family: 'Lato';
        font-style: normal;
        font-weight: 300;
        font-size: 18px;
      }
    }
  }
}
</style>

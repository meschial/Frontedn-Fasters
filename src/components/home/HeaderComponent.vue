<template>
  <div class="header">
    <div class="header-top">
      <div class="text-header">
        <h3 class="top">Elegante é ter um</h3>
        <h1>ALFAIATE</h1>
        <h3 class="top bottom">para chamar de seu.</h3>
      </div>
      <div class="text_bottom">
        <p>
          AGENDE HOJE, <span>PAGUE EM ATÉ 3X<br> COM 12% DE DESCONTO</span> E TENHA<br> 10 MESES PARA CONFECCIONAR!
        </p>
      </div>
      <div class="orcamento_buttom">
        <a href="#" class="a_button">faça um orçamento</a>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'HeaderComponent',
  components: {
  }
}
</script>
<style lang="scss" scoped>
@import '@/assets/scss/_main.scss';
.header{
  position: absolute;
  width: 100%;
  height: 630px;
  left: 0px;
  top: 0px;
  background-image: url('../../assets/img/banner.png');
  .header-top{
    flex: 0 0 50%;
    max-width: 50%;
    position: relative;
    width: 100%;
    .text-header{
      margin: 150px 0 0 250px;
      width: 405px;
      .top{
        font-family: 'Playfair Display';
        font-style: italic;
        font-weight: normal;
        font-size: 32.5627px;
        line-height: 0.1px;
        color: $bage;
      }
      h1{
        font-family: 'Playfair Display';
        font-style: normal;
        font-weight: normal;
        font-size: 90.0346px;
        line-height: 120px;
        text-transform: uppercase;
        color: rgba(2, 75, 104, 0.68);
      }
      .bottom{
        float: right;
      }
    }
    .text_bottom{
      margin: 90px 0 0 250px;
      width: 405px;
      p{
        font-family: 'Lato';
        font-style: normal;
        font-weight: 300;
        font-size: 24px;
        color: $branco;
        span{
          font-weight: 400;
        }
      }
    }
    .orcamento_buttom{
      margin-left:250px;
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

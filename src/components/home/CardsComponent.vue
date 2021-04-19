<template>
  <div class="cards_fav">
    <div class="row" style="margin-right:0;">
      <div class="col-4">
        <div class="card_fav">
          <img src="../../assets/img/fav1.png" alt="">
          <h3>Qualidade</h3>
          <span>Camisaria e Alfaiataria 100% artesanal.</span>
        </div>
      </div>
      <div class="col-4">
        <div class="card_fav">
          <img src="../../assets/img/fav2.png" alt="">
          <div class="text">
            <h3 class="bord">Qualidade</h3>
            <span>Atendimento personalizado no escritório ou residência.</span>
          </div>
        </div>
      </div>
      <div class="col-4">
        <div class="card_fav">
          <img src="../../assets/img/fav3.png" alt="">
            <h3>Experiência</h3>
            <span>Tradição e modernidade proporcionando elegância.</span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'CardsComponent'
}
</script>

<style lang="scss" scoped>
@import '@/assets/scss/_main.scss';
.cards_fav{
  text-align: center;
  .card_fav{
    text-align: center;
    align-items: center;
    padding: 50px 0;
    img{
      width: 36px;
    }
    h3{
      font-family: 'Cormorant';
      font-style: normal;
      text-transform: uppercase;
      font-weight: 600;
      font-size: 24px;
      color: #1C86A4;
      margin: 5px 0 0 0;
    }
    span{
      font-family: 'Lato';
      font-style: normal;
      font-weight: 300;
      font-size: 14px;
      color: #727272;
    }
  }
  .text{
    border-left: 1px solid #CCCCCC;
    border-right: 1px solid #CCCCCC;
  }
}
</style>

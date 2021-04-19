<template>
  <div class="depoimentos">
    <div class="text">
      <h1>Depoimentos</h1>
      <div class="borde"></div>
      <img src="../../assets/img/foto.png">
      <p>
        “Sou cliente do Renee há uns 12 anos. Nosso primeiro contato foi por intermédio de <br>meu pai, que já têm uma história de décadas com o querido Renee.<br>
        O excelente atendimento antes e pós venda e a alta qualidade dos materiais usados<br> colocam a Renee Trajar em um patamar acima dos demais do ramo.”
      </p>
      <span class="title">William H. M. Garey</span><br>
      <span class="slog">Advogado  |   Nelson Garey Advogados Associados</span>
    </div>
    <div class="fundoazul"></div>
  </div>
</template>

<script>
export default {
  name: 'ContactComponent'
}
</script>

<style lang="scss" scoped>
@import '@/assets/scss/_main.scss';
.depoimentos{
  background-image: url('../../assets/img/fundep.png');
  background-repeat: no-repeat;
  position: absolute;
  width: 100%;
  background-size: 100%;
  height: 500px;
  .fundoazul{
    position: absolute;
    background: rgba(29, 28, 87, 0.856);
    width: 100%;
    height: 100%;
    top: 0;
    z-index: -1;
  }
  .text{
    text-align: center;
    margin: 50px 0;
    .borde{
      margin-left: 915px;
      margin-bottom: 40px;
      width: 80px;
      border-top: 1px solid #70B0C4;
    }
    h1{
      font-family: 'Cormorant';
      font-style: normal;
      font-weight: 300;
      font-size: 38px;
      color: #F2F2F2;
    }
    img{
      margin-bottom: 20px;
    }
    p{
      font-family: 'Cormorant';
      font-style: italic;
      font-weight: 300;
      font-size: 26px;
      line-height: 31px;
      text-align: center;
      color: #C4C4C4;
      margin-bottom: 20px;
    }
    .title{
      font-family: 'Cormorant';
      font-style: normal;
      font-weight: normal;
      font-size: 20px;
      line-height: 24px;
      text-align: center;
      color: #BE9667;
    }
    .slog{
      font-family: 'Lato';
      font-style: normal;
      font-weight: 300;
      font-size: 14px;
      color: #949494;
    }
  }
}
</style>

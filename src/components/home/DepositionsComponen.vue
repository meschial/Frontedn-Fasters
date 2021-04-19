<template>
  <div class="depositions">
    <div class="col8">
      <div class="team5"></div>
      <div class="text">
        <span>
          “Faço roupas com o Renee Trajar há mais de duas décadas, o
          serviço é impecável em todos os detalhes, desde a  costura ao
          caimento. O Renee tem uma equipe de mestre!”
        </span>
      </div>
      <div class="text2">
        <h3>Nelson Garey</h3>
        <span>Advogado  |  Nelson Garey Advogados Associados</span>
      </div>
    </div>
    <div class="col4">
      <div class="team4"></div>
      <div class="team3">
        <img src="../../assets/img/team2.png">
      </div>
      <div class="team">
        <img src="../../assets/img/team2.png" alt="">
      </div>
      <div class="team2">
        <img src="../../assets/img/team.png" alt="">
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import '@/assets/scss/_main.scss';
.depositions{
  background: #EFF7F9;
  float: left;
  width: 100%;
  height: 361px;
  .col8{
    width: 60%;
    float: left;
    .text{
      text-align: center;
      width: 650px;
      margin-left: 25%;
      margin-top: 70px;
      span{
        font-family: 'Lato';
        font-style: normal;
        font-weight: 300;
        font-size: 24px;
        color: #828282;
      }
    }
    .text2{
      text-align: center;
      margin-top: 50px;
      margin-left: 25%;
      width: 650px;
      h3{
        font-family: 'Cormorant';
        font-style: italic;
        font-weight: 400;
        font-size: 28px;
        color: $azul;
      }
      span{
        font-family: 'Lato';
        font-style: normal;
        font-weight: 300;
        font-size: 20px;
        color: #BE9667;
      }
    }
    .team5{
      position: absolute;
      width: 47%;
      height: 58%;
      margin-left: 691px;
      background-image: url('../../assets/img/fundo.png');
      background-repeat: no-repeat;
    }
  }
  .col4{
    float: right;
    width: 35%;
    .team3{
      border: 15px solid #fff;
      position: absolute;
      transform: rotate(8deg);
      height: 325px;
      margin-left: 133px;
      width: 235px;
      margin-top: 13px;
      img{
        display: none;
      }
    }
    .team{
      float: left;
      position: absolute;
      margin-left: 110px;
      img{
        height: 360px;
      }
    }
    .team2{
      float: right;
    }
    .team4{
      position: absolute;
      background: rgba(2, 75, 104, 0.81);
      width: 313px;
      height: 360px;
      margin-left: 353px;
    }
  }
}

</style>

<template>
  <div class="storys">
    <div class="row">
      <div class="col-4">
        <div class="img_story">
          <img src="../../assets/img/mask.png" alt="Story Renee">
        </div>
      </div>
      <div class="col-8">
        <div class="text-top">
          <div class="title">
            <h2>Renee Trajar</h2>
          </div>
          <div class="text">
            <p>
              Com mais de 35 anos de experiência em camisas, calças e ternos sob medida,
              possuímos profissionais experientes e altamente qualificados.
            </p>
            <p>
              Cada cliente tem seu molde exclusivamente desenvolvido para seu biotipo através das medidas tiradas pelo próprio Sr. Renee.
            </p>
          </div>
          <div class="text-blue">
            <img src="../../assets/img/aspas.png" alt="aspas">
            <p>
              “Nosso objetivo é superar a expectativa do cliente proporcionando-lhe satisfação <br>
              ao usar nossos produtos, aliado a um relacionamento franco e honesto, <br>
              valorizando o ser humano.”
            </p>
          </div>
          <div class="agendar_visita">
            <a href="#" class="a_button">Agente uma visita!</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'StoryComponent'
}
</script>

<style lang="scss" scoped>
@import '@/assets/scss/_main.scss';
.storys{
  margin-top: 630px;
  padding: 80px 180px;
  .img_story{
    margin-left: 65px;
  }
  .text-top{
    margin-left: 150px;
    .title{
      width: 165px;
      font-family: Cormorant;
      font-style: normal;
      font-weight: 300;
      font-size: 38px;
      color: $azul;
      border-bottom: 1px solid #70B0C4;
    }
    .text{
      max-width: 700px;
      font-family: 'Lato';
      font-weight: 300;
      font-style: light;
      font-size: 19px;
      line-height: 27px;
      margin-top: 50px;
    }
    .text-blue{
      img{
        position: absolute;
        top: 70%;
        left:80%;
        transform:translate(-50%, -50%);
      }
      max-width: 750px;
      font-family: 'Cormorant';
      font-weight: 300;
      font-style: light;
      font-size: 24px;
      color: #1C86A4;
      margin-top: 30px;
    }
    .agendar_visita{
      margin-top:41px;
      .a_button{
        color: $azul;
        text-decoration: none;
        border: 1px solid $azul;
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

<template>
<div class="block">
  <div class="depoimentos">
    <div class="text">
      <h1>Contato</h1>
      <div class="borde"></div>
      <div class="row">
        <div class="col-5">
          <div class="contacts">
            <h1>Telefones</h1>
            <span>+55 (11) 3088-0757</span>
            <h1>E-mail</h1>
            <span>renee@reneetrajar.com.br</span>
            <h2>Atendimento Personalizado</h2>
            <div class="orcamento_buttom">
              <a href="#" class="a_button">Clique aqui!</a>
            </div>
          </div>
        </div>
          <div class="col-7">
            <div class="forms">
              <input type="text" class="form-control" placeholder="Nome"><br>
              <input type="email" class="form-control" placeholder="E-mail"><br>
              <textarea class="form-control" rows="3" placeholder="Mensagem"></textarea>
            </div>
            <div class="enviar">
              <a href="#" class="a_button">Enviar Mensagem</a>
            </div>
        </div>
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: 'ContactComponent'
}
</script>

<style lang="scss" scoped>
@import '@/assets/scss/_main.scss';
.block{
  position: relative;
  margin-top: 600px;
}
.depoimentos{
  max-width: 1175px;
  margin: auto;
  .text{
    text-align: center;
    font-family: 'Cormorant';
    font-style: normal;
    font-weight: 300;
    color: #1C86A4;
    h1{
      font-size: 38px;
    }
    .borde{
      margin-left: 555px;
      margin-bottom: 40px;
      width: 80px;
      border-top: 1px solid #70B0C4;
    }
    .contacts{
      text-align: left;
      font-family: 'Lato';
      font-style: normal;
      font-weight: 300;
      h1{
        font-family: 'Lato';
        font-style: normal;
        font-weight: 300;
        font-size: 18px;
        text-transform: uppercase;
        color: #1C86A4;
        margin: 20px 0 0 0;
      }
      span{
        font-family: 'Lato';
        font-style: normal;
        font-weight: 300;
        font-size: 16px;
        color: #828282;
      }
      h2{
        font-family: 'Lato';
        font-style: normal;
        font-weight: 300;
        font-size: 18px;
        text-transform: uppercase;
        color: #1C86A4;
        margin-top: 77px;
      }
      .orcamento_buttom{
        margin-top: 15px;
        .a_button{
          color: $azul;
          text-decoration: none;
          text-transform: uppercase;
          border:1px solid $azul;
          padding: 8px 80px;
          font-family: 'Lato';
          font-style: normal;
          font-weight: 300;
          font-size: 18px;
        }
      }
    }
    .forms{
      input, textarea{
        border: 1px solid #1C86A4;
        box-sizing: border-box;
        border-radius: 3px;
      }
    }
    .enviar{
      margin-top: 30px;
      .a_button{
        color: $branco;
        text-decoration: none;
        background: #014561;
        border-radius: 2px;
        padding: 10px 267px;
        font-family: 'Lato';
        font-style: normal;
        font-weight: 300;
        font-size: 18px;
      }
    }
  }
}
</style>

<template>
  <div class="footer">
    <div class="row">
      <div class="col-6">
        <img src="../assets/img/logo.png"><br>
        <span>CNPJ:04.487.685/0001-01</span>
      </div>
      <div class="col-6">
        <div class="text">
          <span>
            Copyright: 2021 © Renee Trajar - Todos os direitos reservados.
          </span>
        </div>
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
.footer{
  max-width: 1175px;
  margin: auto;
  .row{
    border-top: 1px solid #BE9667;
    margin-top: 70px;
    padding: 20px 0;
    img{
      width: 165px;
    }
    span{
      font-family: 'Poppins';
      font-style: normal;
      font-weight: 300;
      font-size: 14px;
      line-height: 21px;
      color: #BDBDBD;
      margin-bottom: 50px;
    }
    .text{
      text-align: right;
      margin-top: 90px;
    }
  }
}
</style>

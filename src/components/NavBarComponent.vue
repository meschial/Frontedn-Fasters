<template>
<div class="navbar">
  <div class="nav-left">
    <img src="../assets/img/logo1.png">
  </div>
  <div class="nav-itens">
    <div class="menu">
      <ul>
        <li>empresa</li>
        <li>camisaria</li>
        <li>alfaiataria</li>
        <li>depoimentos</li>
        <li>contato</li>
      </ul>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: 'NavBarComponent'
}
</script>

<style lang="scss" scoped>
@import '@/assets/scss/_main.scss';
.navbar{
  position: fixed;
  top:0;
  width: 100%;
  height: 111px;
  z-index: 9;
  background: linear-gradient(180deg, #000000 29.73%, rgba(0, 0, 0, 0) 100%);
  .nav-left{
    flex: 0 0 50%;
    max-width: 50%;
    position: relative;
    width: 100%;
    img{
      width: 150px;
    }
  }
  .nav-itens{
    flex: 0 0 50%;
    max-width: 50%;
    position: relative;
    width: 100%;
    .menu{
      float: right;
      ul{
        li{
          list-style:none;
          display: inline;
          color: $cinza;
          font-family: 'Lato';
          font-weight: 300;
          font-size: 16px;
          margin-right: 50px;
          text-transform: uppercase;
        }
      }
    }
  }
}
</style>

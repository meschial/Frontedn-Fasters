  <template>
  <div id="app">
    <NavBarComponent />
      <main>
        <router-view/>
        <back-to-top visibleoffset="500"><b-icon icon="arrow-up"></b-icon></back-to-top>
      </main>
      <FooterComponent />
  </div>
</template>

<script>
import NavBarComponent from '@/components/NavBarComponent'
import FooterComponent from '@/components/FooterComponent'
export default {
  name: 'DashboardComponent',
  components: {
    NavBarComponent,
    FooterComponent
  }
}
</script>

<style lang="scss">
.vue-back-to-top{
  -webkit-box-shadow: 7px 9px 12px -2px #000000;
  box-shadow: 7px 9px 12px -2px #000000;
  background-color: #FFFFFF;
  border-radius: 4px;
  width: 50px;
  height: 50px;
  svg{
    font-size: 25px;
    margin: 15px 14px;
  }
  .default{

    span{
      display: none;
    }
  }
}
</style>

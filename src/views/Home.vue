<template>
  <div class="content">
    <HeaderComponent />
    <StoryComponent />
    <DepositionsComponen />
    <CardsComponent />
    <TuxedoComponent />
    <ShirtComponent />
    <TailoringComponent />
    <TestimonyComponent />
    <ContactComponent />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderComponent from '@/components/home/HeaderComponent'
import StoryComponent from '@/components/home/StoryComponent'
import DepositionsComponen from '@/components/home/DepositionsComponen'
import CardsComponent from '@/components/home/CardsComponent'
import TuxedoComponent from '@/components/home/TuxedoComponent'
import ShirtComponent from '@/components/home/ShirtComponent'
import TailoringComponent from '@/components/home/TailoringComponent'
import TestimonyComponent from '@/components/home/TestimonyComponent'
import ContactComponent from '@/components/home/ContactComponent'
export default {
  name: 'Home',
  components: {
    HeaderComponent,
    StoryComponent,
    DepositionsComponen,
    CardsComponent,
    TuxedoComponent,
    ShirtComponent,
    TailoringComponent,
    TestimonyComponent,
    ContactComponent
  }
}
</script>
<style lang="scss" scoped>
@import '@/assets/scss/_main.scss';
</style>

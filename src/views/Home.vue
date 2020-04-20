<template>
  <div class="home">
    <HeaderBoons />
    <HeroBoons />
    <WomanBoons />
    <InstaBoons />
    <PartnerBoons />
    <FooterBoons />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderBoons from '@/components/HeaderBoons.vue'
import HeroBoons from '@/components/HeroBoons.vue'
import WomanBoons from '@/components/WomanBoons'
import InstaBoons from '@/components/InstaBoons'
import PartnerBoons from '@/components/PartnerBoons'
import FooterBoons from '@/components/FooterBoons'

export default {
  name: 'Home',
  components: {
    HeaderBoons,
    HeroBoons,
    WomanBoons,
    InstaBoons,
    PartnerBoons,
    FooterBoons
  }
}
</script>

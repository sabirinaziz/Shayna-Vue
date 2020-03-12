<template>
  <div class="home">
    <HeaderShayna/>
    <HeroShayna/>
    <WomenBannerShayna/>
    <InstagramShayna/>
    <PartnerLogoShayna/>
    <FooterShayna/>
  </div>
</template>
<script>
// @ is an alias to /src
import HeaderShayna from '@/components/HeaderShayna.vue';
import HeroShayna from '@/components/HeroShayna.vue';
import WomenBannerShayna from '@/components/WomenBannerShayna.vue';
import InstagramShayna from '@/components/InstagramShayna.vue';
import PartnerLogoShayna from '@/components/PartnerLogoShayna.vue';
import FooterShayna from '@/components/FooterShayna.vue';

export default {
  name: 'Home',
  components: {
    HeaderShayna,
    HeroShayna,
    WomenBannerShayna,
    InstagramShayna,
    PartnerLogoShayna,
    FooterShayna
  }
}
</script>

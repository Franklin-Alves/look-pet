<template>
  <div class="home">
    <Carousel />
    <FeaturedProducts />
    <ContentSection />
  </div>
</template>

<script>
import Carousel from '../components/Home/Carousel.vue'
import FeaturedProducts from '../components/Home/FeaturedProducts.vue'
import ContentSection from '../components/Home/ContentSection.vue'


export default {
  name: 'Home',
  components: {
    Carousel,
    FeaturedProducts,
    ContentSection
  }
}
</script>

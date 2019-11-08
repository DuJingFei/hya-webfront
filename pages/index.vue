<template>
  <div class="default-container">
     <carousel/>
     <div class="default-main">
        <great-examples/>
     </div>
  </div>
</template>

<script>
import Carousel from '~/components/Carousel'
import GreatExamples from '~/components/GreatExamples'
export default {
  components: {
    Carousel,
    GreatExamples
  },
  data() {
    return {

    }
  },
  created() {

  }
}
</script>

<style lang="less">
.default-container {
   .default-main {
      margin: 0 auto;
   }
}
</style>

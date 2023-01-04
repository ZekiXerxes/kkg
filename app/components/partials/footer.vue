<template>
  <footer class="footer -mx-4 md:mx-0">
    <div class="container mx-auto pb-6 flex justify-center">
      
      <a href="">
     <div class="text-center p-3" style="color:white">
      © 2023 Copyright: Kids Kingdom
    </div>
      </a>
    </div>
  </footer>
</template>
<script lang="ts">
import { Component, Vue } from 'nuxt-property-decorator';
@Component
export default class Footer extends Vue {}
</script>
<style lang="scss">
.footer {
  background-color: $bluise;
}
</style>

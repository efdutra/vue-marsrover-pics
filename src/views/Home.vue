<template>
  <div class="home-container d-flex justify-content-center mt-5">
    Home Content goes here
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component({
  components: {},
})
export default class HomeView extends Vue {}
</script>

<style lang="scss" scoped>
.home-container {
  border: solid 1px green;
}
</style>

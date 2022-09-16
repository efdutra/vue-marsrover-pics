<template>
  <div class="footer-container d-flex mt-auto justify-content-center">
    Footer Here
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
.footer-container {
  border: solid 1px red;
}
</style>

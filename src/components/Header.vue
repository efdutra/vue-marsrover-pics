<template>
  <div class="header-container d-flex w-100 align-items-center justify-content-center">
    Header Here
    <b-avatar />
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
.header-container {
  min-height: 50px;
  border:solid 1px red;
}
</style>

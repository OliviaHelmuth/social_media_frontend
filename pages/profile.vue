<template>
  <div>
    <navbar></navbar>
    <div class="pageContainer w3-light-gray">
      <profile-card></profile-card>
      <post-form></post-form>
      <friend-request></friend-request>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">
.pageContainer {
  height: calc(100vh - 46.5px);
}
</style>

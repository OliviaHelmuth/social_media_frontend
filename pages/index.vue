<template>
  <div class="w3-light-gray">
    <div class="w3-bar w3-theme-d1">
      <ul>
        <nuxt-link to="/">
          <li
            class="nav-link w3-bar-item w3-button w3-hover-white w3-padding-large"
          >
            <font-awesome-icon :icon="['fas', 'home']" />
          </li>
        </nuxt-link>
      </ul>
    </div>
    <div class="w3-content" id="loginContainer">
      <login></login>
      <sign-up></sign-up>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">
#loginContainer {
  height: calc(100vh - 46.5px);
  display: flex;
  justify-content: space-evenly;
  align-items: center;
}
</style>

<template>
  <div class="w3-bar w3-theme-d1">
    <ul>
      <nuxt-link to="/">
        <li class="nav-link w3-bar-item w3-button w3-hover-white w3-padding-large">
          <font-awesome-icon :icon="['fas', 'home']" />
        </li>
      </nuxt-link>
      <nuxt-link to="/profile">
        <li class="nav-link w3-bar-item w3-button w3-hover-white w3-padding-large">
          <font-awesome-icon :icon="['fas', 'user']" />
        </li>
      </nuxt-link>
      <nuxt-link to="/chat">
        <li class="nav-link w3-bar-item w3-button w3-hover-white w3-padding-large">
          <font-awesome-icon :icon="['fas', 'envelope']" />
        </li>
      </nuxt-link>
    </ul>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">
</style>

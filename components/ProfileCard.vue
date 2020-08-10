<template>
  <div class="w3-card w3-round w3-white w3-quarter w3-padding">
    <div class="w3-container">
      <h4 class="w3-center">My Profile</h4>
      <p class="w3-center">
        <img
          id="avatarIcon"
          src="../pictures/avatar-icon.png"
          alt="avatar"
          class="w3-circle"
        />
      </p>
      <hr />
    </div>
    <p class="w3-padding w3-text-theme">
      <font-awesome-icon :icon="['fas', 'briefcase']" />
    </p>
    <p class="w3-padding w3-text-theme">
      <font-awesome-icon :icon="['fas', 'home']" />
    </p>
    <p class="w3-padding w3-text-theme">
      <font-awesome-icon :icon="['fas', 'birthday-cake']" />
    </p>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">
#avatarIcon {
  height: 100px;
}
</style>

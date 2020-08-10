<template>
  <div class="w3-card w3-round w3-white w3-center w3-padding w3-quarter">
    <p class="w3-margin">Friend Request</p>
    <img
      src="../pictures/avatar-icon.png"
      alt="avatar"
      class="w3-circle"
      id="friendRequestAvatar"
    />
    <p class="w3-margin">name of friend</p>
    <div class="w3-row w3-opacity">
      <div class="w3-half">
        <button class="w3-button w3-green w3-block">
          <font-awesome-icon :icon="['fas', 'check']" />
        </button>
      </div>
      <div class="w3-half">
        <button class="w3-button w3-red w3-block">
          <font-awesome-icon :icon="['fas', 'times']" />
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">
#friendRequestAvatar {
  height: 50px;
}
</style>

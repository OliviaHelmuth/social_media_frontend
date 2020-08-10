<template>
  <div class="w3-card w3-round w3-white w3-half">
    <div class="w3-container w3-padding">
      <form method="post">
        <input
          class="w3-input w3-border w3-padding w3-margin-top w3-margin-bottom"
          type="text"
          placeholder="Whats's on your mind ?"
          name="statusPost"
        />
        <button class="w3-button w3-theme w3-margin-bottom" type="submit">
          <font-awesome-icon :icon="['fas', 'pen']" />
          Post
        </button>
      </form>
    </div>
  </div>
</template>

<script>
export default {}
</script>
<style lang="scss"></style>

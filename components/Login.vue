<template>
  <div class="login-card w3-third">
    <div class="w3-card-4">
      <div class="w3-container w3-theme-d1">
        <h2>Log in</h2>
      </div>
      <form class="w3-container w3-white" @submit.prevent="handleLogin">
        <p class="w3-margin-top w3-margin-bottom">
          <label>
            <b>Username</b>
          </label>
          <input
            v-model="loginUsername"
            class="w3-input w3-border"
            name="username"
            type="text"
          />
        </p>
        <p class="w3-margin-top w3-margin-bottom">
          <label>
            <b>Password</b>
          </label>
          <input
            v-model="loginPassword"
            class="w3-input w3-border"
            name="password"
            type="password"
          />
        </p>
        <p>
          <button class="w3-button w3-theme-d1 w3-margin-bottom">Log in</button>
        </p>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      loginUsername: '',
      loginPassword: '',
    }
  },
  methods: {
    handleLogin() {
      
    },
  },
  mounted() {
    this.$axios.$get('http://localhost:8000/content_api/test/')
    .then(response => {
          this.apiData = response.data;
          console.log(this.apiData)
        });
  },
}
</script>

<style></style>

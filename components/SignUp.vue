<template>
        <div class="login-card w3-third">
        <div class="w3-card-4">
          <div class="w3-container w3-theme-d1">
            <h2>Sign up</h2>
          </div>
          <form class="w3-container w3-white" action="/action_page.php">
            <p class="w3-margin-top w3-margin-bottom">
              <label>
                <b>Username</b>
              </label>
              <input class="w3-input w3-border" name="username" type="text" />
            </p>
            <p class="w3-margin-top w3-margin-bottom">
              <label>
                <b>Password</b>
              </label>
              <input class="w3-input w3-border" name="password" type="password" />
            </p>
            <p class="w3-margin-top w3-margin-bottom">
              <label>
                <b>Email</b>
              </label>
              <input class="w3-input w3-border" name="email" type="email" />
            </p>
            <p>
              <button class="w3-button w3-theme-d1 w3-margin-bottom">Register</button>
            </p>
          </form>
        </div>
      </div>
</template>

<script>
export default {

}
</script>

<style>

</style>
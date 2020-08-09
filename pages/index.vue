<template>
  <div>
    <div class="w3-bar w3-theme-d1">
      <ul>
        <nuxt-link to="/">
          <li class="nav-link w3-bar-item w3-button w3-hover-white w3-padding-large">
            <font-awesome-icon :icon="['fas', 'home']" />
          </li>
        </nuxt-link>
      </ul>
    </div>
    <div>
      <div class="login-card w3-third">
        <div class="w3-card-4">
          <div class="w3-container w3-theme-d1">
            <h2>Log in</h2>
          </div>
          <form class="w3-container" action="/action_page.php">
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
            <p>
              <button class="w3-btn w3-theme-d1 w3-margin-bottom">Register</button>
            </p>
          </form>
        </div>
      </div>
      <div class="login-card w3-third">
        <div class="w3-card-4">
          <div class="w3-container w3-theme-d1">
            <h2>Sign up</h2>
          </div>
          <form class="w3-container" action="/action_page.php">
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
              <button class="w3-btn w3-theme-d1 w3-margin-bottom">Register</button>
            </p>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">
.login-card {
  margin: 5rem;
}
</style>

<template lang="html">
  <div class="">
    <section class="section">
      <div class="login">
        <div class="login-header">
          <h2 class="login-title">Login</h2>
        </div>
        <form action="" class="login-form">
          <div class="login-form__group">
            <label for="Email">Email</label>
            <input class="login-form__input"type="text" placeholder="Email">
          </div>
          <div class="login-form__group">
            <label for="password">Password</label>
            <input class="login-form__input"type="text" placeholder="Password">
          </div>
          <div class="login-form__buttons">
            <router-link class="button button-register" :to="{ name: '/register' }">Register</router-link>
            <router-link class="button button-login" :to="{ name: '/login' }">Login</router-link>
          </div>
        </form>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  data() {
    return {
    };
  },

  methods: {

  },
};
</script>

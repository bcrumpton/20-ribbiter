<template lang="html">
  <div class="app">
    <section class="section">
      <div class="welcome">
        <h2 class="welcome-heading">Welcome to Ribbiter!</h2>
        <router-link class="welcome-btn welcome-btn__register" :to="{ name: 'register' }">Register</router-link>
        <router-link class="welcome-btn welcome-btn__login" :to="{ name: 'login' }">Login</router-link>
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

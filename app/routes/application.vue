<template lang="html">
  <div class="">
    <nav class="nav">
      <div class="nav-left">
        <router-link :to="{ name: 'index' }" class="nav-item">Ribbeter</router-link>
      </div>
      <div class="nav-right">
        <router-link :to="{ name: 'index' }" class="nav-item">Ribbets</router-link>
        <router-link :to="{ name: 'index' }" class="nav-item">Frogs</router-link>
        <router-link :to="{ name: 'index' }" class="nav-item">Login</router-link>
      </div>
    </nav>
    <div class="container">
      <section class="section">
        <router-view></router-view>
      </section>
    </div>
  </div>
</template>

<script>
import Index from './index.vue';
import Login from '/routes/login.vue';
import Register from '/routes/register.vue';
import Users from 'routes/users.vue';
export default {
  components: {
    Index,
    Login,
    Register,
    Users
  },
  data() {
    return {
    };
  },

  methods: {

  },
};
</script>

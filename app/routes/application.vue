<template lang="html">
  <div class="">
    <nav class="nav">
      <div class="nav-left">
        <router-link :to="{ name: 'index' }" class="nav-item">Ribbeter</router-link>
      </div>
      <div class="nav-right">
        <router-link :to="{ name: 'index' }" class="nav-item">Ribbets</router-link>
        <router-link :to="{ name: 'index' }" class="nav-item">Frogs</router-link>
        <router-link :to="{ name: 'login' }" class="nav-item">Login</router-link>
      </div>
    </nav>
    <div class="container">
      <router-view></router-view>
    </div>
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

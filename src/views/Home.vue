<template>
  <div class="home">
    <a class="button is-danger" @click="login()">SignIn with Google</a>
  </div>
</template>

<script>
import { mapActions} from 'vuex';

export default {
  name: 'home',
  methods: mapActions('auth', ['login']), 
};
</script>


<template>
  <v-app dark>
    <AppBar/>
    <v-content>
      <v-container>
        <nuxt />
      </v-container>
    </v-content>
  </v-app>
</template>
<script>
import AppBar from './AppBar'

export default {
  data() {
    return {};
  },
  components:{
    AppBar,
  }
};
</script>

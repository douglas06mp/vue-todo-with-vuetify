<template>
  <v-app class="grey lighten-4">
    <Navbar/>
    <v-content class="background">
        <router-view></router-view>
    </v-content>
  </v-app>
</template>

<script>
import Navbar from '@/components/Navbar'
export default {
  name: 'App',
  data: () => ({

  }),
  components: {
    Navbar
  }
};
</script>

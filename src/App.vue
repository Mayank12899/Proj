<template>
  <v-app>

    <v-app-bar color = "primary" max-height="50">
    </v-app-bar>
    <sidenav/>
    Work / Doesn't Work
    </v-app>
</template>

<script>
import sidenav from './components/sidenav';
export default {
  name: 'App',

  components: {
    sidenav,
  },

  data: () => ({
    //
  }),
};
</script>

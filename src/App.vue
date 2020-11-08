<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
      <div class="d-flex align-center">
        <h2>Jerry's Parallax Scrolling Demo</h2>
      </div>

      <v-spacer></v-spacer>

    </v-app-bar>

    <v-main>
      <!-- <HelloWorld/> -->
      <v-container>
        <BackgroundPic/>
        <Table/>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
// import HelloWorld from './components/HelloWorld';
import Table from './components/Table';
import BackgroundPic from './components/BackgroundPic';

export default {
  name: 'App',

  components: {
    Table,
    BackgroundPic
  },

  data: () => ({
    //
  }),
};
</script>

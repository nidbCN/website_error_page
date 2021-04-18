<template>
  <v-app>
    <v-app-bar
        app
        color="primary"
        dark
    >
      Gaein nidb
    </v-app-bar>

    <v-main>
      <v-container>
        <MainView/>
      </v-container>

    </v-main>
  </v-app>
</template>

<script>
import MainView from './components/MainView';

export default {
  name: 'App',
  components: {
    MainView,
  },
  data: () => ({}),
};
</script>

<template>
  <v-app>
    <v-system-bar app>
    </v-system-bar>
    
    <v-app-bar clipped-left app >
    </v-app-bar>

    <v-navigation-drawer clipped  app>
    </v-navigation-drawer>

    <v-main>

      <v-container fluid>

        <router-view></router-view>
      </v-container>
    </v-main>

    <v-footer app>
    </v-footer>

    <v-bottom-navigation app>
    </v-bottom-navigation>  
  </v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
  }),
};
</script>

<template>
  <v-app>
    <v-app-bar app color="primary" dark></v-app-bar>

    <v-content>
      <Messages />
    </v-content>
  </v-app>
</template>

<script>
import Messages from "./components/Messages.vue";

export default {
  name: "App",

  components: {
    Messages
  },

  data: () => ({
    //
  })
};
</script>

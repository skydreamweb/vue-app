<template>
  <div>
    <h4>Messages</h4>
    <v-list>
      <v-list-item v-for="message in messages" :key="message.id">
        <v-list-item-content>
          <v-list-item-title v-text="message"></v-list-item-title>
        </v-list-item-content>
      </v-list-item>
    </v-list>

    <ul v-for="message in messages" :key="message.id">
      <li>{{message}}</li>
    </ul>
  </div>
</template>
<script>
export default {
  data() {
    return {
      messages: ["hello world", "vue project"]
    };
  }
};
</script>
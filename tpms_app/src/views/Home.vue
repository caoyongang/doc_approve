<template>
  <div class="home">
    <v-app-bar color="teal darken-2" dark>
      <v-toolbar-title> <v-icon>mdi-ticket-percent</v-icon>Travel Permits Management System</v-toolbar-title>

      <v-spacer></v-spacer>
      <Nav></Nav>
      <v-toolbar-title>Welcome</v-toolbar-title>
    </v-app-bar>
    <Login />
  </div>
</template>

<script>
// @ is an alias to /src
import Login from "@/components/Login.vue";
import Nav from "@/components/Nav.vue"

export default {
  name: "Home",
  components: {
    Login,
    Nav
  },
};
</script>

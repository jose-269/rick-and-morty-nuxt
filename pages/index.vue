<template>
  <v-app>
    <Nav />
    <v-container app>
      <v-row>
        <v-col cols="12" align="center">
          <nuxt-link to="/personajes">
            <img src="@/assets/img/rym-logo.png" alt="logo" width="600" />
          </nuxt-link>
        </v-col>
      </v-row>
    </v-container>
  </v-app>
</template>

<script>
import Nav from "@/components/Nav.vue";
export default {
  name: "app",
  components: {
    Nav
  }
};
</script>
<style scoped>
img {
  cursor: pointer;
}
</style>

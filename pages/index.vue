<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <v-card class="logo py-4 d-flex justify-center">
        <NuxtLogo />
      </v-card>
      <v-card>
        <v-card-actions>
          <v-btn
            class="btn"
            color="primary"
            nuxt
            to="/inspire"
          >
            지갑연결
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-col>
  </v-row>
</template>
<style scoped>
.btn{
  margin: auto;
}
</style>
<script>
export default {
  name: 'IndexPage'
}
</script>

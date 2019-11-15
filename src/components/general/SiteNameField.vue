<template>
  <v-col cols="12" md="4">
    <v-text-field v-model="siteName" label="Name of site" outlined />
  </v-col>
</template>

<script>
export default {
  name: "site-name-field",
  data: () => ({
    siteName: null
  })
};
</script>

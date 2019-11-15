<template>
  <v-col cols="12" md="4">
    <v-text-field v-model="locationName" label="Location" outlined />
  </v-col>
</template>

<script>
export default {
  name: "LocationNameField",
  data: () => ({
    locationName: null
  })
};
</script>

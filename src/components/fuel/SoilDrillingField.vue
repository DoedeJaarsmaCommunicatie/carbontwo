<template>
  <v-col cols="12" md="4">
    <v-text-field
      v-model="soilDrillingDays"
      label="How many days of a soil drilling machine do you forsee?"
      outlined
      type="number"
    />
  </v-col>
</template>

<script>
export default {
  name: "SoilDrillingField",
  data: () => ({
    soilDrillingDays: null
  })
};
</script>

<style scoped></style>

<template>
  <v-col cols="12" md="4">
    <v-text-field
      v-model="carDistance"
      label="Is electricity produced by a diesel aggregate?"
      outlined
      type="number"
    />
  </v-col>
</template>

<script>
export default {
  name: "DrivingCarsField",
  data: () => ({
    carDistance: null
  })
};
</script>

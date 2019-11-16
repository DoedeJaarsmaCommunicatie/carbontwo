<template>
  <v-col cols="12" md="4">
    <v-text-field
      v-model="carDistance"
      label="How many kilometers for a car to drive do you expect?"
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

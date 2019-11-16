<template>
  <v-col cols="12" md="4">
    <v-text-field
      v-model="vanDistance"
      label="How many kilometers for a van do you expect?"
      outlined
      type="number"
    />
  </v-col>
</template>

<script>
export default {
  name: "DrivingVansField",
  data: () => ({
    vanDistance: null
  })
};
</script>

<style scoped></style>

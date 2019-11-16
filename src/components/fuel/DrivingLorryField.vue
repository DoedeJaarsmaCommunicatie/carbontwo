<template>
  <v-col cols="12" md="4">
    <v-text-field
      label="How many kilometers for a 15 tonnes lorry do you expect?"
      hint="(transport of equipement)"
      persistent-hint
      outlined
      v-model="lorryDistance"
    />
  </v-col>
</template>

<script>
export default {
  name: "DrivingLorryField",
  data: () => ({
    lorryDistance: null,
  })
};
</script>

<style scoped></style>

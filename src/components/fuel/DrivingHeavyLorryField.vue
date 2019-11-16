<template>
  <v-col cols="12" md="4">
    <v-text-field
      v-model="heavyLorryDistance"
      label="How many kilometers for a 50 tonnes lorry do you expect?"
      persistent-hint
      hint="(transport of excavated soil)"
      outlined
      type="number"
    />
  </v-col>
</template>

<script>
export default {
  name: "DrivingHeavyLorryField",
  data: () => ({
    heavyLorryDistance: null
  })
};
</script>

<style scoped></style>

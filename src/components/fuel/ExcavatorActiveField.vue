<template>
  <v-col cols="12" md="4">
    <v-text-field
      outlined
      label="How many days will an excavator be active on the site?	"
      type="number"
      v-model="excavatorActive"
    />
  </v-col>
</template>

<script>
export default {
  name: "ExcavatorActiveField",
  data: () => ({
    excavatorActive: null
  })
};
</script>

<style scoped></style>

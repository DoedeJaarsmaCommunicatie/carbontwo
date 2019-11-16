<template>
  <v-col cols="12" md="4">
    <v-checkbox
      v-model="dieselAggregate"
      label="Is electricity produced by a diesel aggregate?"
    />
  </v-col>
</template>

<script>
export default {
  name: "ElectricityProducerField",
  data: () => ({
    dieselAggregate: false
  })
};
</script>

<style scoped></style>

<template>
  <v-col cols="12" md="4">
    <v-text-field
      v-model="electricityUsage"
      label="Electricity usage project [kWh]"
      outlined
      type="number"
      min="200"
    />
  </v-col>
</template>

<script>
export default {
  name: "ElectricityUsageField",
  data: () => ({
    electricityUsage: 200
  })
};
</script>

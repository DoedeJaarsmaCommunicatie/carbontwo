<template>
  <v-col cols="12" md="4">
    <v-text-field
      v-model="waterUsage"
      label="Water usage project [cubic metres]"
      outlined
      type="number"
      min="10"
    />
  </v-col>
</template>

<script>
export default {
  name: "WaterUsageField",
  data: () => ({
    waterUsage: 200
  })
};
</script>

<template>
  <v-col cols="12" md="4">
    <v-text-field
      v-model="gasUsage"
      label="Gas usage project [cubic metres]"
      outlined
      type="number"
      min="100"
    />
  </v-col>
</template>

<script>
export default {
  name: "GasUsageField",
  data: () => ({
    gasUsage: 200
  })
};
</script>

<template>
  <v-form>
    <v-container>
      <h2>Consumption of electricity, water & gas</h2>
      <v-row>
        <electricity-producer-field />
        <electricity-usage-field />
        <water-usage-field />
        <gas-usage-field />
      </v-row>
    </v-container>
  </v-form>
</template>

<script>
import ElectricityProducerField from "./ElectricityProducerField";
import ElectricityUsageField from "./ElectricityUsageField";
import WaterUsageField from "./WaterUsageField";
import GasUsageField from "./GasUsageField";
export default {
  name: "EWGConsumption",
  components: {
    GasUsageField,
    WaterUsageField,
    ElectricityUsageField,
    ElectricityProducerField
  }
};
</script>

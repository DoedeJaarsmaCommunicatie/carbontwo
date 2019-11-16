<template>
  <v-form>
    <v-container>
      <h2>Consumption of fuel based on diesel</h2>
      <v-row>
        <driving-cars-field />
        <driving-vans-field />
        <driving-lorry-field />
        <excavator-active-field />
        <soil-drilling-field />
        <driving-heavy-lorry-field />
      </v-row>
    </v-container>
  </v-form>
</template>

<script>
import DrivingCarsField from "./DrivingCarsField";
import DrivingVansField from "./DrivingVansField";
import DrivingLorryField from "./DrivingLorryField";
import ExcavatorActiveField from "./ExcavatorActiveField";
import SoilDrillingField from "./SoilDrillingField";
import DrivingHeavyLorryField from "./DrivingHeavyLorryField";

export default {
  name: "FuelConsuption",
  components: {
    DrivingHeavyLorryField,
    SoilDrillingField,
    ExcavatorActiveField,
    DrivingLorryField,
    DrivingVansField,
    DrivingCarsField
  }
};
</script>

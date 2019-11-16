<template>
  <v-app>
    <header-component />

    <v-content>
      <v-container>
        <general-input-component />
        <e-w-g-consumption />
        <fuel-consuption />
      </v-container>
    </v-content>

    <footer-component />
  </v-app>
</template>

<script>
import FooterComponent from "./components/FooterComponent";
import HeaderComponent from "./components/HeaderComponent";
import GeneralInputComponent from "./components/general/GeneralInput";
import EWGConsumption from "./components/ewg/EWGConsumption";
import FuelConsuption from "./components/fuel/FuelConsuption";

export default {
  name: "app",
  components: {FuelConsuption, EWGConsumption, GeneralInputComponent, HeaderComponent, FooterComponent }
};
</script>

<style lang="scss">
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

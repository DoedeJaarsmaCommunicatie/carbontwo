<template>
  <v-form>
    <v-container>
      <h2>General Information</h2>
      <v-row>
        <site-name-field />
        <location-name-field />
      </v-row>
    </v-container>
  </v-form>
</template>

<script>
import SiteNameField from "./SiteNameField";
import LocationNameField from "./LocationNameField";
export default {
  name: "general-input-component",
  components: { LocationNameField, SiteNameField }
};
</script>

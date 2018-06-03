<template>
  <v-app dark>
      <v-toolbar>
      <v-layout row>
        <v-flex xs6>
      <v-text-field 
      name="searchbox"
      label="Search songs and artists ..."
      single-line
      ></v-text-field></v-flex></v-layout>
    <v-toolbar-title>viet rap 2018</v-toolbar-title>
    <v-spacer></v-spacer>
    <v-toolbar-items class="hidden-sm-and-down">
      <v-btn flat>Sign up</v-btn>
      <v-btn flat>Sign in</v-btn>
    </v-toolbar-items>
  </v-toolbar>

    
  <v-toolbar dark color="primary" dense>
  <v-layout row justify-center>
  <v-toolbar-items class="text-xs-center">
  <div class="text-xs-center">
      <v-btn flat>Home</v-btn>
      <v-btn flat>artirts</v-btn>
      <v-btn flat>Add songs</v-btn>
      <v-btn flat>All Songs</v-btn>
      </div>
    </v-toolbar-items>
  </v-layout>
  </v-toolbar>
  </v-app>
</template>

<script>
  export default {
    data () {
      return {
      }
    }
  }
</script>

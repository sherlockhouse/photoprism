<template>
  <div>
    <v-toolbar flat color="secondary" :dense="$vuetify.breakpoint.smAndDown">
      <v-toolbar-title>
        <translate>Not implemented yet</translate>
      </v-toolbar-title>

      <v-spacer></v-spacer>
    </v-toolbar>

    <v-container>
      <p>
        Issues labeled <a href="https://github.com/photoprism/photoprism/labels/help%20wanted">help wanted</a> /
        <a href="https://github.com/photoprism/photoprism/labels/easy">easy</a> can be good (first)
        contributions.
        Our <a href="https://github.com/photoprism/photoprism/wiki">Developer Guide</a> contains all information
        necessary to get you started.
      </p>
    </v-container>
  </div>
</template>

<script>
export default {
  name: 'people',
  data() {
    return {};
  },
  methods: {}
};
</script>

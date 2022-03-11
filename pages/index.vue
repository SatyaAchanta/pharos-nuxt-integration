<template>
  <main>
    <homepage-pharos-button variant="primary">This is Button</homepage-pharos-button>
     <homepage-pharos-heading level="1" preset="7">This is Button</homepage-pharos-heading>
  </main>
</template>

<script lang="ts">
import Vue from 'vue'
import { PharosAlert, PharosButton, PharosHeading } from '@ithaka/pharos';
import registerComponents from '@ithaka/pharos/lib/utils/registerComponents';
import "@ithaka/pharos/lib/styles/fonts.css";
import "@ithaka/pharos/lib/styles/variables.css";


registerComponents('homepage', [PharosAlert, PharosButton, PharosHeading]);

export default Vue.extend({
  name: 'IndexPage'
})
</script>

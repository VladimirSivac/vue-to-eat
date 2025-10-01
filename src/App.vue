<script lang="ts">
import TheNavbar from './components/TheNavbar.vue'

export default {
  components: {
    TheNavbar,
  },
  data: () => ({
    tagline: 'Test String',
  }),
}
</script>

<template>
  <TheNavbar :tagline="tagline" />
  <RouterView />
</template>

<style></style>

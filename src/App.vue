<template>
  <div class="container-sm">
    <name-component />
  </div>
</template>

<script>
import NameComponent from '@/components/NameComponent.vue'

export default {
  name: 'App',
  components: {
    NameComponent,
  },
}
</script>

<style scoped>
  .container-sm {
    max-width: 680px;
  } 
</style>


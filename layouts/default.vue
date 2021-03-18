<template>
  <div class="relative bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6">
      <Header />
      <Nuxt />
    </div>
  </div>
</template>
<script>
import Header from '~/components/Header'
export default {
  name: 'Default',
  components: {
    Header,
  },
}
</script>

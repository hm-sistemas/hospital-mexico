<template>
  <NuxtLink
    class="text-base font-medium text-gray-500 hover:text-gray-900"
    :to="to"
  >
    {{ title }}
  </NuxtLink>
</template>
<script>
export default {
  name: 'NavLink',
  props: { to: String, title: String },
}
</script>

<template>
  <NuxtLink
    :to="to"
    class="-m-3 p-3 flex items-start rounded-lg hover:bg-gray-50"
  >
    <slot></slot>
    <div class="ml-4">
      <p class="text-base font-medium text-gray-900">{{ title }}</p>
      <p class="mt-1 text-sm text-gray-500">
        {{ description }}
      </p>
    </div>
  </NuxtLink>
</template>
<script>
export default {
  name: 'DropdownLink',
  props: { to: String, title: String, description: String },
}
</script>

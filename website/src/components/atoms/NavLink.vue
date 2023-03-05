<template>
  <a class="text-gray-500 transition hover:text-gray-500/75" :href="link">
    <slot />
  </a>
</template>

<script lang="ts">
export default {
  props: {
    link: {
      type: String,
      required: true
    }
  },
  data() {
    return {}
  },
}
</script>
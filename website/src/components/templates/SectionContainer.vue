<template>
  <section class="grid">
    <div class="max-w-7xl justify-self-center grid px-5">
      <slot />
    </div>
  </section>
</template>

<script lang="ts">
export default {
  data() {
    return {
      test: 'World'
    }
  }
}
</script>
<style></style>
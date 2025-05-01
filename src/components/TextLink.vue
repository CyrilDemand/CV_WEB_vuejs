<script setup>
defineProps({
  label: {
    type: String,
    required: true,
  },
  link: {
    type: String,
    required: true,
  },
})
</script>

<template>
  <a
    class="font-medium text-slate-200 hover:text-teal-300 focus-visible:text-teal-300"
    :href="link"
    target="_blank"
    rel="noreferrer noopener"
    :aria-label="`${label} (opens in a new tab)`"
    >{{ label }}</a
  >
</template>

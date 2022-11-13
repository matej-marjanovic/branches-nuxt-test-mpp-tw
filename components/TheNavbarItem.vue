<template>
  <li class="my-4">
    <a
      :class="{
        underline: route.name == href || (route.name == 'index' && href == '/'),
      }"
      class="
        text-base
        decoration-2
        underline-offset-4
        font-bold
        text-gray-500
        transition
        hover:text-gray-500/75
      "
      :href="href"
    >
      <slot></slot>
    </a>
  </li>
</template>

<script lang="ts" setup>
const route = useRoute();

const props = defineProps({
  currentItem: {
    type: Boolean,
    default: false,
  },
  href: {
    type: String,
    default: '#',
  },
});
</script>

<script setup lang="ts">
const ready = useState('ready', () => false);

const count = ref(0);

const compTemplate = computed(
  () =>
    `
<div class='border'>
    <div>hello i'm defined in the setup of app.vue</div>
    <div>This component's template is in a computed refreshed on count</div>
    count:` +
    count.value +
    `.
    I don\'t recommend you to do this for performance issue, prefer passing props for mutable data.
</div>`
);

/**
 * most of the time, vue compiler need at least a VNode, use h() from vue to define and render the component
 */
const ComponentDefinedInSetup = computed(() =>
  h({
    template: compTemplate.value,
  })
);
</script>

<template>
  <!-- Edit this file to play around with Nuxt but never commit changes! -->
  <div>
    <ComponentDefinedInSetup />
  </div>
</template>

<style>
.border {
  border: 1px solid burlywood;
}
</style>

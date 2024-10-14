<template>
  <div>Hello World</div>
</template>
<script setup>
const { $toast } = useNuxtApp();
onMounted(() => {
  $toast.success("😃 Yay!!!");
  $toast.warning("😬 Oops!!!");
  $toast.error("😟 Ehhhh!!!");
});
</script>

<template>
  <div>Hello World</div>
</template>
<script setup>
const { $toast } = useNuxtApp();
$toast.success("😃 Yay!!!");
$toast.warning("😬 Oops!!!");
$toast.error("😟 Ehhhh!!!");
</script>

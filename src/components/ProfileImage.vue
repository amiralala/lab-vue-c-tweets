<script setup>
const props = defineProps({image:String});
</script>

<template>
<!-- src="https://i.imgur.com/9yw1Fyw.jpg" -->
<img
      :src="image"
      class="profile"
      alt="profile"
    />
</template>

<style>

</style>
<script lang="ts" setup>
import { ref } from "@vue/composition-api";

const res = ref('333')
console.log(res);

</script>
<template>
  <div class="about">
    {{res}}
    <h1>This is an about page</h1>
  </div>
</template>

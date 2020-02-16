<template>
  <div>
    <div v-for="data in list" :key="data">
      {{ data }}
    </div>
  </div>
</template>

<script>
export default {
  inject: ['list'],
};
</script>

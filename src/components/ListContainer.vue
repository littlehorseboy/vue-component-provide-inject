<template>
  <div>
    <ListSection :list="list" />
  </div>
</template>

<script>
import ListSection from './ListSection';

export default {
  components: {
    ListSection,
  },
  props: {
    list: Array,
  },
};
</script>

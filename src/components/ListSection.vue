<template>
  <div>
    <List :list="list" />
  </div>
</template>

<script>
import List from './List';

export default {
  components: {
    List,
  },
  props: {
    list: Array,
  },
};
</script>

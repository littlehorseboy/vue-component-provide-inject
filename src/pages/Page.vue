<template>
  <div>
    <ListContainer :list="list" />
  </div>
</template>

<script>
import ListContainer from '@/components/ListContainer';

export default {
  components: {
    ListContainer,
  },
  data() {
    return {
      list: [
        '吃飯',
        '睡覺',
        '打東東',
      ],
    };
  },
};
</script>

<template>
  <div>
    <ListContainer />
  </div>
</template>

<script>
import ListContainer from '@/components/ListContainer';

export default {
  components: {
    ListContainer,
  },
  provide() {
    return {
      list: this.list,
    };
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

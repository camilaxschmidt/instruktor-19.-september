<script>
import { ref } from 'vue';
export default {
  setup() {
    const aNumber = ref(3);

    function test(event) {
      console.log('test');
    }

    return {
      test,
      aNumber,
    };
  },
};
</script>

<template>
  <div>@click="test" style = "height": 100%; width: 100%; background</div>
</template>

<style></style>

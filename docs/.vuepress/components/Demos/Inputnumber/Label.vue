<template lang="html">
  <div class="centerx">
    <vs-input-number v-model="number0" label="passengers:" />
    <vs-input-number v-model="number1" label-right="kg" />
  </div>
</template>

<script>
export default {
  data() {
    return {
      number0: 1,
      number1: 1
    };
  }
};
</script>

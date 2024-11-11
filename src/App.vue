<template>
  <q-btn label="Click Me" color="primary" @click="handleClick" />
</template>

<script>
export default {
  methods: {
    handleClick() {
      alert("Button clicked!");
    },
  },
};
</script>

<template>
  <div>
    <p v-if="showMessage" >{{ message }}</p>
    <button @click="showMessage = !showMessage">Show/Hide</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: "I Start Learning Vue.js",
      showMessage:true,
    }
  }
};
</script>

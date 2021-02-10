<template>
  <div id="app container-centered">
    <input
      v-model="message"
      type="text">
      <h2 class="message">{{ message }}</h2>
      <h3>Another Message</h3>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: 'Light Boilerplate',
    };
  },
};
</script>

<style>

.container-centered {
  display:grid;
  place-items: center;
}

.message {
  font-size: 18px;
  font-family: 'Roboto', sans-serif;
  color: blue;
}
</style>
<template>
  <div class="about">
    <h1>Info Page</h1>
    <button @click="getParams">Get Params</button>
  </div>
</template>

<script>
export default {
  name: "NotFound",
  methods: {
    getParams() {
      console.log(this.$route.params);
    },
  },
};
</script>

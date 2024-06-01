<template>
  <div class="about">
    <h1>404 page not found</h1>
    <button @click="navigateBack">Go Back</button>
  </div>
</template>

<script>
export default {
  name: "NotFound",
  //   props: ["person"],
  methods: {
    navigateBack() {
      console.log(this.$route.params);
      //   this.$router.go(-1);
      this.$router.push({ name: "home" });
    },
  },
};
</script>

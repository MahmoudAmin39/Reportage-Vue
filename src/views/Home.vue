<template>
  <div>
    <Button text="Sign In"/><Button text="Register"/>
  </div>
</template>

<script>
  import Button from "../components/Button.vue";

  export default {
    name: "Home",
    components: {
      Button
    }
  }
</script>
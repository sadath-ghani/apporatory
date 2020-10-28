<template>
  <div id="app">
    <Background />
    <SignUpForm />
  </div>
</template>

<script>
import Background from "./components/Background.vue";
import SignUpForm from "./components/SignUpForm.vue";

export default {
  name: "App",
  components: {
    Background,
    SignUpForm
  }
};
</script>

<template>
  <HelloWorld />
  <FrontCard class="card-front" />
  <BackCard class="card-back" />
  <Form class="main-form" />
</template>

<script setup>
import HelloWorld from "./components/HelloWorld.vue";
import FrontCard from "./components/FrontCard.vue";
import BackCard from "./components/BackCard.vue";
import Form from "./components/Form.vue";
</script>

<style scoped>
.main-form {
  position: absolute;
  top: 30%;
  left: 55%;
}

.card-front {
  position: absolute;
  top: 20%;
  left: 12%;
}

.card-back {
  position: absolute;
  top: 50%;
  left: 20%;
}
</style>

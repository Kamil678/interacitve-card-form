<template>
  <div class="back-card">
    <div class="cvc-card">CVC</div>
  </div>
</template>

<script setup></script>

<style scoped>
.back-card {
  width: 400px;
  height: 200px;
  background-image: url(../images/bg-card-back.png);
  border-radius: 10px;
  background-size: cover;
}

.back-card img {
  position: absolute;
  left: 5%;
  top: 10%;
  width: 70px;
}

.back-card div {
  position: absolute;
  bottom: 40%;
  right: 15%;
  background-color: transparent;
  border: none;
}
</style>

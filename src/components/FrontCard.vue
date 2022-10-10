<template>
  <div class="front-card">
    <img src="../images/card-logo.svg" />
    <div class="number" placeholder="number">Number</div>
    <div class="name" placeholder="name">Name</div>
    <div class="date" placeholder="date">Date</div>
  </div>
</template>
<script setup></script>

<style scoped>
.front-card {
  width: 400px;
  height: 200px;
  background-image: url(../images/bg-card-front.png);
  background-size: cover;
  border-radius: 10px;
}

.front-card img {
  position: absolute;
  left: 5%;
  top: 10%;
  width: 70px;
}

.front-card div {
  position: absolute;
  bottom: 10%;
  color: white;
  background-color: transparent;
  border: none;
}

div.number {
  left: 5%;
  bottom: 25%;
  font-size: 20px;
}

div.name {
  left: 5%;
  font-size: 15px;
}

div.date {
  left: 80%;
  font-size: 15px;
}
</style>

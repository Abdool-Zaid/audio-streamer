<script setup></script>

<template>
<div id="carouselExampleDark" class="carousel carousel-dark slide" data-bs-ride="carousel">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1" aria-label="Slide 2"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item  maxBody active" data-bs-interval="10000">
    <h1>main</h1>
    </div>
    <div class="carousel-item maxBody " data-bs-interval="2000">
      <h1>nav</h1>
  </div>
  </div>
</div>
</template>

<style >

.maxBody{
  width: 100vw;
  height: 100vh;
}</style>

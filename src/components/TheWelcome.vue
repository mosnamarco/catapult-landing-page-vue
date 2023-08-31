<template>
  <div class="wrapper">
    <div class="container">
      <p>
        <strong><span>CATAPULT</span></strong> your taste into<br />the NEXT LEVEL!!!
      </p>
    </div>

    <!-- Landing Page Background -->
    <div class="background_filter"></div>
    <div class="background_image">
      <img src="src/assets/images/bread.jpeg" alt="" />
    </div>
  </div>
</template>

<style scoped>
.wrapper {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100%;
  width: 100%;
}
.container {
  width: 100%;
  font-size: 60px;
  margin-inline: 10%;
}
span {
  color: gold;
  font-family: 'Kelly Slab', cursive;
}
p {
  font-family: 'Dancing Script', cursive;
}
.background_filter,
.background_image {
  height: 100%;
  width: 100%;
  position: fixed;
  top: 0;
  left: 0;
}
.background_filter {
  z-index: -1;
  background-image: linear-gradient(black, transparent);
}
.background_image {
  z-index: -2;
}
.background_image img {
  width: 100%;
  height: 100%;
}
</style>

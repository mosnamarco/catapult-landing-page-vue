<template>
  <div class="navbar">
    <p><a href="/">CATAPULT</a></p>
    <ul>
      <li><a href="/about">About</a></li>
      <li><a href="#">Products</a></li>
      <li><a href="#">Contact Us</a></li>
    </ul>
  </div>
</template>

<style scoped>
.navbar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-direction: row;
  height: 100px;
  margin-inline: 10%;
}
ul {
  display: flex;
  justify-content: center;
  gap: 20px;
}
li {
  list-style: none;
}
a {
    text-decoration: none;
    color: white;
}
p a {
  color: gold;
  font-family: 'Kelly Slab', cursive;
}
</style>

<template>
  <div class="container">
    <div class="image">
      <slot name="product-image"></slot>
    </div>

    <div class="price">
      <p>
        <slot name="product-price"></slot>
      </p>
    </div>

    <div class="description">
      <span>
        <slot name="product-name"></slot>
      </span>
      <span>
        <slot></slot>
      </span>
    </div>

    <button>Avail Now!</button>
  </div>
</template>

<style scoped>
.container {
  padding: 20px;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  text-align: center;
  gap: 20px;
  height: 350px;
  width: fit-content;
  background-color: rgba(65, 65, 65, 0.418);
  border-radius: 20px;
}
.container:hover {
    animation: throb 500ms infinite alternate;
}

@keyframes throb {
    0% {
        box-shadow: 0px 0px 0px 0px gold;
        scale: 1;
    }
    100% {
        scale: 1.1;
        box-shadow: 0px 0px 50px 10px green;
    }
}
</style>

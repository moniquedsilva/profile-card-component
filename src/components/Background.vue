<template>
  <div class="background-area">
    <img
      src="assets/bg-pattern-top.svg"
      alt="Background Pattern"
      class="background-top"
    />
    <img
      src="assets/bg-pattern-bottom.svg"
      alt="Background Pattern"
      class="background-down"
    />
  </div>
</template>

<style>
.background-area {
  background-color: var(--dark-cyan);
  width: 100%;
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  position: fixed;
  inset: 0;
  z-index: -1;
}
.background-top {
  width: 70%;
  position: absolute;
  top: -75%;
  left: -23rem;
}
.background-down {
  width: 70%;
  position: absolute;
  bottom: -90%;
  right: -15rem;
}
</style>

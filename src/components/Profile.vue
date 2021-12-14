<template>
  <article class="card">
    <img
      src="assets/bg-pattern-card.svg"
      alt="Background Pattern"
      class="card-image"
    />
  </article>
</template>

<style>
.card {
  background-color: var(--white);
  border-radius: 15px;
  height: 23.44rem;
  width: 87%;
}

.card-image {
  border-radius: 15px 15px 0 0;
  width: 100%;
}

@media (min-width: 24em) {
  .card {
    width: 20.375rem;
  }
}
</style>

<template>
  <section class="card">
    <img
      src="assets/bg-pattern-card.svg"
      alt="Background Pattern"
      class="card-image"
    />
    <div class="testing">
      <article class="card-information">
        <div class="card-subsections">
          <h2>80K</h2>
          <p>Followers</p>
        </div>
        <div class="card-subsections">
          <h2>803K</h2>
          <p>Likes</p>
        </div>
        <div class="card-subsections">
          <h2>1.4K</h2>
          <p>Photos</p>
        </div>
      </article>
    </div>
  </section>
</template>

<style>
.card {
  background-color: var(--white);
  border-radius: 15px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  height: 23.44rem;
  width: 87%;
}

@media (min-width: 24em) {
  .card {
    width: 20.375rem;
  }
}

.card-image {
  border-radius: 15px 15px 0 0;
  width: 100%;
}

.card-information {
  border-top: 1px solid hsla(0, 0%, 91%, 1);
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  gap: 1.5rem;
  height: 89px;
  padding: 1rem 0;
}

@media (min-width: 20em) {
  .card-information {
    gap: 2.5rem;
    padding: 1.25rem 0;
  }
}

.card-subsections {
  cursor: pointer;
  text-align: center;
}

.card-subsections h2 {
  color: var(--dark-blue);
  font-family: var(--kumbh);
  font-size: var(--size);
  margin-bottom: 0.625rem;
}

.card-subsections p {
  color: var(--dark-gray);
  font-family: var(--kumbh);
  font-size: 0.625rem;
  letter-spacing: 1px;
}
</style>

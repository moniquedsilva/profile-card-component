<template>
  <section class="card">
    <img
      src="assets/bg-pattern-card.svg"
      alt="Background Pattern"
      class="card-image"
    />
    <div class="card-profile-area">
      <img
        src="assets/image-victor.jpg"
        alt="Profile picture"
        class="card-profile-img"
      />
      <article class="card-name-area">
        <div class="card-title">
          <h1>Victor Crest</h1>
          <span>26</span>
        </div>
        <p class="card-city">London</p>
      </article>
    </div>
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
  </section>
</template>

<style>
.card {
  background-color: var(--white);
  border-radius: 15px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  height: 23.44rem;
  width: 87%;
  position: relative;
}

@media (min-width: 24em) {
  .card {
    width: 21.81rem;
  }
}

.card-image {
  border-radius: 15px 15px 0 0;
  width: 100%;
}

.card-profile-area {
  display: flex;
  align-items: center;
  flex-direction: column;
  gap: 1.625rem;
  position: absolute;
  top: 4rem;
}

@media (min-width: 21em) {
  .card-profile-area {
    top: 5rem;
  }
}

.card-profile-img {
  width: max-content;
  border-radius: 100%;
  outline: 5px solid white;
}

.card-name-area {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 1rem;
  font-family: var(--kumbh);
}

.card-title {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 0.625rem;
}

.card-title h1 {
  color: var(--dark-blue);
  font-size: var(--size);
}

.card-title span {
  color: var(--grayish-blue);
}

.card-city {
  color: var(--grayish-blue);
  font-size: 1rem;
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
  color: var(--grayish-blue);
  font-family: var(--kumbh);
  font-size: 0.625rem;
  letter-spacing: 1px;
}
</style>

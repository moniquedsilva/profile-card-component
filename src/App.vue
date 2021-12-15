<template>
  <div class="conteiner">
    <Profile />
    <Copyright />
  </div>
</template>

<script>
import Profile from './components/Profile.vue'
import Copyright from './components/Copyright.vue'

export default {
  name: 'App',
  components: {
    Profile,
    Copyright,
  },
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

:root {
  --dark-cyan: hsl(185, 75%, 39%);
  --dark-blue: hsl(229, 23%, 23%);
  --grayish-blue: hsl(227, 10%, 46%);
  --dark-gray: hsl(0, 0%, 59%);
  --white: hsl(0, 0%, 100%);
  --kumbh: 'Kumbh Sans', sans-serif;
  --size: 1.125rem;
}

.conteiner {
  background: url('/assets/bg-pattern-top.svg') bottom 35vh right 53.6vw
      no-repeat,
    url('/assets/bg-pattern-bottom.svg') top 42vh left 48vw no-repeat;
  background-color: var(--dark-cyan);
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-evenly;
  width: 100vw;
  height: 100vh;
}

@media (max-width: 24em) {
  .conteiner {
    background: url('/assets/bg-pattern-top.svg') bottom 35vh right 53.6vw
        no-repeat,
      url('/assets/bg-pattern-bottom.svg') top 34vh left 36vw no-repeat;
    background-color: var(--dark-cyan);
  }
}
</style>

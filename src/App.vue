<template>
  <div class="conteiner">
    <Profile />
    <Copyright />
    <Background />
  </div>
</template>

<script>
import Profile from './components/Profile.vue'
import Copyright from './components/Copyright.vue'
import Background from './components/Background.vue'

export default {
  name: 'App',
  components: {
    Profile,
    Copyright,
    Background,
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
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-evenly;
  width: 100vw;
  height: 100vh;
}
</style>

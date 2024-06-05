<template>
  <div>
      <h1>Olá Vue!</h1>
      <p>Meu nome é {{ nome }}</p>
  </div>
</template>

<script>
import PrimeiroComponente from './PrimeiroComponente.vue';

export default {
  name: 'PrimeiroComponente',
  data() {
      return {
          nome: "Pedro"
      }
  }
}
</script>
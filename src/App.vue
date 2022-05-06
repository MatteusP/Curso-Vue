<template>
  <HeadeR/>
  <PrimeiroComponente/>
  <LifeCycle/>
  <PessoaComp/>
</template>

<script>
import HeadeR from './components/HeadeR.vue'
  import PrimeiroComponente from './components/PrimeiroComponente.vue'
  import LifeCycle from './components/LifeCycle.vue'
  import PessoaComp from './components/PessoaComp.vue'

  export default {
    name: 'AppA',
    components: {
      HeadeR,
      PrimeiroComponente,
      LifeCycle,
      PessoaComp
}
  }
</script>

<style>
  body{
    background-color: #333;
    color: #fff;
  }
  a{
    color: red
  }
</style>

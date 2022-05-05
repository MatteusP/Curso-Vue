<template>
  <PrimeiroComponente/>
  <LifeCycle/>
  <PessoaComp/>
</template>

<script>
  import PrimeiroComponente from './components/PrimeiroComponente.vue'
  import LifeCycle from './components/LifeCycle.vue'
  import PessoaComp from './components/PessoaComp.vue'

  export default {
    name: 'AppA',
    components: {
      PrimeiroComponente,
      LifeCycle,
      PessoaComp
    }
  }

</script>

<template>
  <h1>Olá,</h1>
  <p>Meu nome é {{nome}} e trabalho como {{profissao}}!</p>
</template>

<script>

export default {
  name: 'PrimeiroComponente',
  data(){
    return {
      nome: 'Mateus',
      profissao: 'Programador'
    }
  }
}
</script>


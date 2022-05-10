<template>
  <h1>Olá,</h1>
  <p>Meu nome é {{nome}} e trabalho como {{profissao}}!</p>
  <MultiplosEventos/>
  <ReutilizarComp/>
  <ReutilizarComp/>
</template>

<script>
import MultiplosEventos from './MultiplosEventos.vue'
import ReutilizarComp from './ReutilizarComp.vue'
export default {
    name: "PrimeiroComponente",
    data() {
        return {
            nome: "Mateus",
            profissao: "Programador"
        };
    },
    components: {
    MultiplosEventos,
    ReutilizarComp
    
}
}
</script>
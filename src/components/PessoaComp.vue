<template>
    <h2>Esta é a descrição da pessoa: {{nome}}</h2>
    <InfoUser CompEmail="mattheus@email.com"/>
</template>

<script>
import InfoUser from "./InfoUser"
export default {
    name: "PessoaComp",
    components:{
        InfoUser
    },
    data() {
        return{
            nome: 'Mateus'
        }
    },
}


</script>
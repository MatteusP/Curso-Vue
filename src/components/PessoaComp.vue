<template>
    <h2>Esta é a descrição de pessoa: {{nome}}</h2>
    <InfoUser/>
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

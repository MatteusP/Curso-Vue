<template>
    <h1>Meu nome é: {{nome}}</h1>
</template>

<script>

export default {
    name: 'LifeCycle',
    data(){
        return {
            nome: 'teste'
        }
    },
    created(){
        setTimeout(()=> {
            this.nome = 'Mateus'
        }, 1000)
        
    },
    mounted(){
        setTimeout(()=> {
            this.nome = 'Pedro'
        }, 1000)
    }
}
</script>

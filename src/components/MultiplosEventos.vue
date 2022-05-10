-+7/*<template>
    <div>
        <button @click="primeiro($event), segundo($event)">Ativar Multiplos eventos</button>
        <p>{{multiplos_eventos }}</p>
    </div>
</template>

<script>
export default {
    name: 'MultiplosEventos',
    data() {
        return{
            multiplos_eventos: ""
        }
    },
    //executar varios metodos apenas com um click
    methods:{
        primeiro(){
            this.multiplos_eventos = "primeiro evento"
        },
        segundo(){
            setTimeout(()=> this.multiplos_eventos = "segundo evento", 500)
        }
    }
}
</script>